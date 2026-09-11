# macOS packaging

Native Darwin host:

```sh
make -C packaging/macos
```

writes `packaging/macos/out/<pkg>-<ver>.pkg` via `pkgbuild`.

On non-macOS hosts, use **gh-makerelease** with:

```
<project>/.config/icons-zondicons/macos.build-host
$HOME/.config/icons-zondicons/macos.build-host
```
