# Composition rows (generated — run: node scripts/read-composition-rows.mjs --sample)

31 file(s), 118 row record(s), 38968 bytes, 0 parser warning(s).

| class | rows |
|---|---|
| duplicate-insert-id | 9 |
| field-replacement | 28 |
| insert-entries | 62 |
| skipped-no-id | 16 |
| unknown-metadata-key | 3 |

| file | bytes | coverage | rows |
|---|---|---|---|
| <workspace>//dsh-link/plugins/dsh-agent-context/cordis.patch.yml | 729 | 0.37 | 2 |
| <workspace>//dsh-link/plugins/dsh-continue-button/cordis.patch.yml | 347 | 0.38 | 2 |
| <workspace>//dsh-link/plugins/dsh-delegation-model-choice/cordis.patch.yml | 485 | 0.46 | 2 |
| <workspace>//dsh-link/plugins/dsh-lan-bridge/cordis.patch.yml | 974 | 0.19 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-brand/cordis.patch.yml | 256 | 0.43 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-collab/cordis.patch.yml | 283 | 0.43 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-compat/cordis.patch.yml | 440 | 0.3 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-groups/cordis.patch.yml | 3548 | 0.49 | 14 |
| <workspace>//dsh-link/plugins/dsh-link-host/cordis.patch.yml | 1498 | 0.12 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-markdown/cordis.patch.yml | 381 | 0.33 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-mods/cordis.patch.yml | 7160 | 0.16 | 4 |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 14294 | 0.51 | 34 |
| <workspace>//dsh-link/plugins/dsh-link-notes/cordis.patch.yml | 755 | 0.21 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-panel/cordis.patch.yml | 1612 | 0.38 | 4 |
| <workspace>//dsh-link/plugins/dsh-link-responsive/cordis.patch.yml | 278 | 0.43 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-teams/cordis.patch.yml | 354 | 0.33 | 2 |
| <workspace>//dsh-link/plugins/dsh-link-toolbar/cordis.patch.yml | 241 | 0.5 | 2 |
| <workspace>//dsh-link/plugins/dsh-liquid-glass/cordis.patch.yml | 253 | 0.43 | 2 |
| <workspace>//dsh-link/plugins/dsh-theme-settings/cordis.patch.yml | 279 | 0.43 | 2 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/01-insert-control.patch.yml | 425 | 0.5 | 2 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/02-non-insert-without-id.patch.yml | 252 | 0.2 | 1 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/03-non-insert-missing-target.patch.yml | 192 | 0.4 | 1 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/04-insert-child-legacy-keys.patch.yml | 587 | 0.78 | 3 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/05-insert-duplicate-id.patch.yml | 289 | 0.83 | 4 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/06-disabled-js-expression.patch.yml | 296 | 0.67 | 2 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/07-insert-into-group.patch.yml | 432 | 0.73 | 4 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/08-layer-config-base.patch.yml | 511 | 0.81 | 4 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/09-layer-config-replace.patch.yml | 379 | 0.6 | 2 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/10-disabled-bang-js-expression.patch.yml | 282 | 0.67 | 2 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/11-insert-into-non-group.patch.yml | 623 | 0.63 | 4 |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/12-name-mismatch.patch.yml | 533 | 0.62 | 3 |

<!-- live-inputs:begin -->
## Live-machine inputs (excluded from --check)

Read from this machine, not from the repository: the profile own patch file and bundles installed outside it. The application rewrites its own profile patch, so this material is recorded and printed here and left out of the --check comparison; rows.json carries it under liveInputs.

| file | bytes | lines | rows | digest |
|---|---|---|---|---|
| C:/Users/<user>/AppData/Roaming/dev.dshlink.client/dsh-link/kernel-home/profiles/web/cordis.patch.yml | 5973 | 209 | 127 | ae40cd1e07f5671b |
| …/node_modules/@argszero/cordis-plugin-thinking-loop-guard/cordis.patch.yml | 563 | 17 | 2 | a67aadd6a3685bb7 |
| …/node_modules/dsh-opencode-go/cordis.patch.yml | 60 | 4 | 2 | 092ae27ec8eff9f5 |
| …/node_modules/dsh-repeat-guard/cordis.patch.yml | 316 | 8 | 2 | 9cfb8e37bec05056 |
| …/node_modules/dsh-repetition-guard/cordis.patch.yml | 345 | 10 | 2 | 5b09fb5122e2ae0c |

liveDigest fa9497385c69ee21 over 5 file(s); 7257 bytes, 135 row record(s).


## Layer order (from the live profile manifest, dsh.profile.bundles)

| bundle | layer |
|---|---|
| @deepseek-ai/dsh-base | 0 |
| @deepseek-ai/dsh-web-app | 1 |
| dsh-opencode-go | 2 |
| @deepseek-ai/dsh-experimental-agent-team-profile | 3 |
| @deepseek-ai/dsh-experimental-auto-review | 4 |
| @deepseek-ai/dsh-experimental-voice-input-bundle | 5 |
| dsh-liquid-glass | 6 |
| dsh-theme-settings | 7 |
| dsh-link-mods | 8 |
| dsh-link-collab | 9 |
| dsh-link-teams | 10 |
| dsh-continue-button | 11 |
| dsh-link-brand | 12 |
| dsh-agent-context | 13 |
| @argszero/cordis-plugin-thinking-loop-guard | 14 |
| dsh-lan-bridge | 15 |
| dsh-repetition-guard | 16 |
| dsh-repeat-guard | 17 |
| dsh-delegation-model-choice | 18 |
| dsh-link-groups | 19 |
| dsh-link-notes | 20 |
| dsh-link-markdown | 21 |
| dsh-link-panel | 22 |
| dsh-link-compat | 23 |
| dsh-link-host | 24 |
| dsh-link-responsive | 25 |

The loader keys its store by id, so a later layer with the same id wins; when the winner carries no config, the earlier config is a dead flag. This is the shape recorded at plugins/dsh-link-mods/cordis.patch.yml:25-33.

### Same id in more than one place

| id | layer | where | class | config |
|---|---|---|---|---|
| compaction | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:56 | field-replacement | yes |
| compaction | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:175 | duplicate-insert-id | yes |
| compaction-basic | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:63 | field-replacement | no |
| compaction-basic | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:182 | duplicate-insert-id | no |
| command-compact | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:66 | field-replacement | no |
| command-compact | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:185 | duplicate-insert-id | no |
| tool-result-pruner | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:69 | field-replacement | yes |
| tool-result-pruner | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml:188 | duplicate-insert-id | yes |
| link-panel | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-panel/cordis.patch.yml:21 | insert-entries | yes |
| link-panel | 26 | 26 | <workspace>//dsh-link/plugins/dsh-link-panel/cordis.patch.yml:27 | duplicate-insert-id | no |
| theme-settings | 26 | 26 | <workspace>//dsh-link/plugins/dsh-theme-settings/cordis.patch.yml:5 | insert-entries | no |
| theme-settings | 26 | 26 | C:/Users/<user>/AppData/Roaming/dev.dshlink.client/dsh-link/kernel-home/profiles/web/cordis.patch.yml:37 | field-replacement | yes |
| dsh-link-fixture-duplicate | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/05-insert-duplicate-id.patch.yml:3 | insert-entries | yes |
| dsh-link-fixture-duplicate | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/05-insert-duplicate-id.patch.yml:8 | duplicate-insert-id | yes |
| dsh-link-fixture-group | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/07-insert-into-group.patch.yml:5 | insert-entries | yes |
| dsh-link-fixture-group | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/07-insert-into-group.patch.yml:9 | duplicate-insert-id | no |
| dsh-link-fixture-config-target | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/08-layer-config-base.patch.yml:4 | insert-entries | yes |
| dsh-link-fixture-config-target | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/09-layer-config-replace.patch.yml:4 | field-replacement | yes |
| dsh-link-fixture-nongroup | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/11-insert-into-non-group.patch.yml:7 | insert-entries | yes |
| dsh-link-fixture-nongroup | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/11-insert-into-non-group.patch.yml:10 | duplicate-insert-id | no |
| dsh-link-fixture-name-mismatch | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/12-name-mismatch.patch.yml:6 | insert-entries | yes |
| dsh-link-fixture-name-mismatch | 26 | 26 | <workspace>//dsh-link/compat/adaptation/rows/fixtures/12-name-mismatch.patch.yml:10 | duplicate-insert-id | no |
| dsh-repeat-guard | 26 | 26 | C:/Users/<user>/AppData/Roaming/dev.dshlink.client/dsh-link/kernel-home/profiles/web/cordis.patch.yml:55 | field-replacement | yes |
| dsh-repeat-guard | 17 | 17 | …/node_modules/dsh-repeat-guard/cordis.patch.yml:6 | insert-entries | no |
| thinking-loop-guard | 26 | 26 | C:/Users/<user>/AppData/Roaming/dev.dshlink.client/dsh-link/kernel-home/profiles/web/cordis.patch.yml:189 | field-replacement | yes |
| thinking-loop-guard | 14 | 14 | …/node_modules/@argszero/cordis-plugin-thinking-loop-guard/cordis.patch.yml:15 | insert-entries | no |
| repetition-guard | 26 | 26 | C:/Users/<user>/AppData/Roaming/dev.dshlink.client/dsh-link/kernel-home/profiles/web/cordis.patch.yml:204 | field-replacement | yes |
| repetition-guard | 16 | 16 | …/node_modules/dsh-repetition-guard/cordis.patch.yml:5 | insert-entries | yes |

The later layer wins: layers apply in the order bundle, profile, home, CLI (packages/boot/app-boot/src/config-schema/document.ts:159), so the profile layer overrides a bundle layer that carries the same id.
The live profile carries no dead config today: the duplicate-id shape recorded at plugins/dsh-link-mods/cordis.patch.yml:25-33 was fixed in R3-2d; this table is the current state.

<!-- live-inputs:end -->


## Field-replacement rows whose target is not inserted in the same file

This is the common shape, not an edge case: the live profile patch carries field-replacement rows only.

| file | line | id | target inserted in this file |
|---|---|---|---|
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 39 | persona | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 56 | compaction | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 63 | compaction-basic | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 66 | command-compact | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 69 | tool-result-pruner | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 124 | anchored-lite | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 135 | tool-bash | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 142 | tool-str-replace-editor | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 145 | tool-pwsh | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 150 | tool-fs | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 153 | tool-fs-search | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 159 | tool-jobs | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 163 | skill-filesystem | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 166 | tool-skill | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 170 | tool-goal | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 201 | tool-subagent-control | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 205 | tool-subagent | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 213 | tool-subagent-fork | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 221 | tool-workflow | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 225 | tool-ralph | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 233 | tool-ask-user | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 236 | tool-todo | no |
| <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 241 | tool-web | no |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/03-non-insert-missing-target.patch.yml | 3 | dsh-link-fixture-no-such-row | no |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/08-layer-config-base.patch.yml | 8 | dsh-link-fixture-config-child-a | no |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/08-layer-config-base.patch.yml | 12 | dsh-link-fixture-config-child-b | no |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/09-layer-config-replace.patch.yml | 4 | dsh-link-fixture-config-target | no |
| <workspace>//dsh-link/compat/adaptation/rows/fixtures/09-layer-config-replace.patch.yml | 6 | dsh-link-fixture-config-child-c | no |

## Real samples and constructed fixtures

| source | file | bytes | coverage | rows | insert children |
|---|---|---|---|---|---|
| sample | <workspace>//dsh-link/plugins/dsh-agent-context/cordis.patch.yml | 729 | 7/19 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-continue-button/cordis.patch.yml | 347 | 3/8 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-delegation-model-choice/cordis.patch.yml | 485 | 6/13 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-lan-bridge/cordis.patch.yml | 974 | 4/21 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-brand/cordis.patch.yml | 256 | 3/7 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-collab/cordis.patch.yml | 283 | 3/7 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-compat/cordis.patch.yml | 440 | 3/10 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-groups/cordis.patch.yml | 3548 | 33/67 | 14 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-host/cordis.patch.yml | 1498 | 3/25 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-markdown/cordis.patch.yml | 381 | 3/9 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-mods/cordis.patch.yml | 7160 | 15/96 | 4 | 3 |
| sample | <workspace>//dsh-link/plugins/dsh-link-mods/presets.patch.yml | 14294 | 125/246 | 34 | 2 |
| sample | <workspace>//dsh-link/plugins/dsh-link-notes/cordis.patch.yml | 755 | 3/14 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-panel/cordis.patch.yml | 1612 | 12/32 | 4 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-responsive/cordis.patch.yml | 278 | 3/7 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-teams/cordis.patch.yml | 354 | 3/9 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-link-toolbar/cordis.patch.yml | 241 | 3/6 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-liquid-glass/cordis.patch.yml | 253 | 3/7 | 2 | 1 |
| sample | <workspace>//dsh-link/plugins/dsh-theme-settings/cordis.patch.yml | 279 | 3/7 | 2 | 1 |
| fixture | …/fixtures/01-insert-control.patch.yml | 425 | 5/10 | 2 | 1 |
| fixture | …/fixtures/02-non-insert-without-id.patch.yml | 252 | 1/5 | 1 | 0 |
| fixture | …/fixtures/03-non-insert-missing-target.patch.yml | 192 | 2/5 | 1 | 0 |
| fixture | …/fixtures/04-insert-child-legacy-keys.patch.yml | 587 | 14/18 | 3 | 1 |
| fixture | …/fixtures/05-insert-duplicate-id.patch.yml | 289 | 10/12 | 4 | 2 |
| fixture | …/fixtures/06-disabled-js-expression.patch.yml | 296 | 6/9 | 2 | 1 |
| fixture | …/fixtures/07-insert-into-group.patch.yml | 432 | 11/15 | 4 | 2 |
| fixture | …/fixtures/08-layer-config-base.patch.yml | 511 | 13/16 | 4 | 1 |
| fixture | …/fixtures/09-layer-config-replace.patch.yml | 379 | 6/10 | 2 | 0 |
| fixture | …/fixtures/10-disabled-bang-js-expression.patch.yml | 282 | 6/9 | 2 | 1 |
| fixture | …/fixtures/11-insert-into-non-group.patch.yml | 623 | 10/16 | 4 | 2 |
| fixture | …/fixtures/12-name-mismatch.patch.yml | 533 | 8/13 | 3 | 1 |

Coverage is attributed lines over total lines: comment-only and blank lines are not attributed, and any content line the parser could not attribute is listed in rows.json under unattributedLines.

## Class coverage

| class | real samples | fixtures | note |
|---|---|---|---|
| insert-entries | 41 | 21 | 01-insert-control.patch.yml, 04-insert-child-legacy-keys.patch.yml, 05-insert-duplicate-id.patch.yml, 06-disabled-js-expression.patch.yml, 07-insert-into-group.patch.yml, 08-layer-config-base.patch.yml, 10-disabled-bang-js-expression.patch.yml, 11-insert-into-non-group.patch.yml, 12-name-mismatch.patch.yml |
| field-replacement | 23 | 5 | 03-non-insert-missing-target.patch.yml, 08-layer-config-base.patch.yml, 09-layer-config-replace.patch.yml |
| skipped-no-id | 15 | 1 | 02-non-insert-without-id.patch.yml |
| unknown-metadata-key | 2 | 1 | 04-insert-child-legacy-keys.patch.yml |
| duplicate-insert-id | 5 | 4 | 05-insert-duplicate-id.patch.yml, 07-insert-into-group.patch.yml, 11-insert-into-non-group.patch.yml, 12-name-mismatch.patch.yml |
| unresolvable-insert-name | 0 | 0 | no trigger on this machine: neither the real samples nor the fixtures exercise this class |

Nested rows: 49 record(s) carry origin "nested" with nestedUnder set to the line of the row whose value holds them. These are entry lists inside a config block (a preset declaring its own plugins, for example); the root patch index does not see them, so treating them as layer rows manufactures targets that nobody has to fix.


## What this report cannot see

- a !!js value is kept verbatim and never evaluated
- whether the module a row names is actually installed
- group inheritance and layer order beyond the file being read (bundle, profile, home, CLI apply in that order, per document.ts:152-159)
- a config block is reported as present, never as satisfying any schema
- anchors, aliases, block scalars and multi-document files are counted, not parsed (see the module header)
