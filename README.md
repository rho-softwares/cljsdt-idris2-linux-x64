# @cljsdt/idris2-linux-x64

Idris 2 0.8.0 on Chez Scheme 10.4.1 for [cljsdt](https://github.com/rho-softwares/cljsdt), Linux x64:
relocatable (`./idris2` finds everything next to itself) and trimmed to what cljsdt uses (Idris's
`prelude` and `base`; no Chez-compiled library code). Depends on the system's libc and libm only.

Built from the sources by cljsdt's `scripts/idris2-package.sh` (Chez with threads, without curses
and X11; Idris without the RefC backend's support). Licenses: Idris 2 (BSD-3-Clause) and Chez Scheme
(Apache-2.0), in `licenses/`.
