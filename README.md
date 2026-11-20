# slint

xlings-res payload for **`slint`**: Slint's C++ SDK (`libslint_cpp`, its headers and `slint-compiler`), built from the release tag with upstream CMake's default features.

| | |
|---|---|
| upstream | https://github.com/slint-ui/slint |
| license | GPL-3.0-only OR LicenseRef-Slint-Royalty-free-2.0 OR LicenseRef-Slint-Software-3.0 |
| build | [`xim-pkgindex/.agents/tools/slint/build-slint.sh`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/slint) on native runners |
| recipe | [`xim-pkgindex/pkgs/s/slint.lua`](https://github.com/openxlings/xim-pkgindex/blob/main/pkgs/s/slint.lua) |
| consumer | mcpp-index `compat.slint`, `mcpplibs.mwrap.slint` |

Assets per release: `slint-<version>-<profile>-<os>-<arch>.{tar.gz,zip}` and `.sha256` sidecars; GitHub and GitCode are byte-identical. Each archive's `BUILD-INFO.txt` names the tag, features, toolchain and CI run.
