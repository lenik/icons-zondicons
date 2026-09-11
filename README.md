# icons-zondicons
`icons-zondicons` is a Meson-based **Bash** CLI template using [bash-shlib](http://uni.bodz.net/base/bash-shlib) (`import cliboot`).
`icons-zondicons` is the example script under `src/`.

## Build / install

```bash
sudo apt install meson ninja-build asciidoctor bash-shlib
meson setup /build
ninja -C /build
meson install -C /build
```

## Example

```bash
icons-zondicons [OPTION]... [FILE]...
```

## License

Copyright (C) 2026 Lenik <icons-zondicons@bodz.net> — **AGPL-3.0-or-later**. See `LICENSE`.
