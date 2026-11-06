# dsh-cross-version-loader

Resolve a DeepSeek Harness kernel version against declarative compatibility tables so plugin bundles can load across kernel versions.

## Contents

- compat/surface/<kernel-version>.json: observed loader/plugin surface of one kernel version.
- compat/table/<kernel-version>.ts: typed capability table per version (what a plugin may rely on and how it degrades).
- src/: resolution helpers (version match, capability lookup, degradation).
- scripts/link-kernel-deps.mjs: link a kernel checkout against a plugin set for local development.

## Usage

node scripts/link-kernel-deps.mjs <kernel-dir> <plugin-dir>

## License

MIT