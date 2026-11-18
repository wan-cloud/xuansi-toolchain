# xuansi-toolchain

The xuansi WASM/AOT **toolchain distributions**: wamrc builds (from the
wan-cloud WAMR/llvm forks — sources stay in the forks) and the llvm-dev
packages, served as GitHub Releases plus `toolchain-index.json`.

- Stable index entry: `releases/latest/download/toolchain-index.json`
  (single-stream repo: every release carries the regenerated index).
- `wasi_sdk` assets point at the upstream WebAssembly/wasi-sdk releases
  (not hosted here).
- `toolchain-index.json` keeps `index_ver: 1` — the toolchain index's
  own schema, unchanged by the drivers index's v2.

Migrated 2026-11-18 (dist wave A9) from wan-cloud/xuansi-drivers —
byte-identical assets (sha256-verified against the pre-migration index
pins). The old releases stay frozen in place on the drivers repo.

License: Apache-2.0 (see LICENSE) — matching the build sources'
licenses; see each release's manifest.json for the exact source pins.
