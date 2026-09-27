# sdcc

The Small Device C Compiler — this package builds the **6502 and Z80** ports (plus their assemblers/linkers), with non-free libraries excluded.

Prebuilt binaries, packaged and published by [retropack](https://github.com/retropack/retropack).

## Install

```sh
mise install github:retropack/sdcc
```

Static binaries, no runtime dependencies. `test.sh` compiles for `z80` and `mos6502` from an arbitrary directory, proving the relocatable `include/` + `lib/` lookup.

## Licence

GPL-2.0 — see <https://sourceforge.net/projects/sdcc/>. Binaries are redistributed under the upstream licence; each release archive ships the upstream `COPYING`/`LICENSE` plus a `RETROPACK-NOTICE` identifying the exact source and build.

Source and build logic live in [retropack/retropack](https://github.com/retropack/retropack).
