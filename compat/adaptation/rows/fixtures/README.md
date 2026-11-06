# Row fixtures

One file per 0.1.x-era patch idiom, plus index.json: the format id (dsh-link.row-fixtures/1),
the question each file asks, and what the documentation says about it (a citation, or an
explicit statement that the documentation is silent). The files carry inputs and questions;
verdicts belong to the row reader and to the real loader probe.

Conventions these files hold to:

- Each file is one profile layer patch: a top-level YAML array of patch mappings. The loader
  requires an array and rejects a mapping; that is stated in the overlay seed comment in
  src-tauri/src/core/profile.rs and in the composition reference (SKILL.md line 12).
- Carriers are the Cordis builtin "cordis:group", so no fixture depends on which plugin
  packages a machine has installed. 02 and 03 name no row on purpose: naming nothing is the
  idiom they exercise.
- 08 and 09 are a pair: 08 is the base layer, 09 the replacing layer applied over it.
- Nothing here asserts an expected verdict. The one field that cites documentation lives in
  index.json, and it says so when the documentation is silent.

## Parsing trap (measured while writing these)

"!!js" and "!js" are Loader expressions, not YAML-standard tags. A generic YAML parser
refuses them unless the tag type is registered, so validating these files with the kernel
own js-yaml (read only, no install) needs custom types:

    new jsyaml.Type('tag:yaml.org,2002:js', { kind: 'scalar', construct: (data) => data })
    new jsyaml.Type('!js', { kind: 'scalar', construct: (data) => data })

Without them, load() throws for 06 and 10. A reader that reads such a throw as "this is not
a row" would drop exactly the two idioms those files exist to exercise.

Measured with the real 0.2.1 loader (scripts/probe-row-behaviour.mjs, composition stage): the
two spellings behave differently, and the difference is not per-row. "!!js" composes (06
reports one row added, no diagnostics). "!js" aborts the parse of the whole layer:

    Error: dsh: failed to parse overlay <fixtures>/10-disabled-bang-js-expression.patch.yml:
    YAMLException: unknown tag !<!js> (8:27)

so on that layer the dump produces no tree at all (the probe reports exit 1 and an empty
composition). A reader has to classify the single-bang spelling as layer-fatal, not as an
unknown row.
