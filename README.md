# grep

GNU grep 3.11 (with -P, Perl regular expressions)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install grep
```

| | |
|---|---|
| Version | 3.11 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | [`pcre2`](https://github.com/Artfical/tpkg-pcre2), [`bash`](https://github.com/Artfical/tpkg-bash) |
| Needs tOS build | 619 or newer |
| Size | 93048 bytes (179160 unpacked) |
| SHA-256 of the `.tpkg` | `37a8a2a86655856de39cdb520e60065e18fa9553303552ea7545d26b115fba8d` |

## Commands it adds

| Command | Runs |
|---|---|
| `egrep` | `bin/egrep` |
| `fgrep` | `bin/fgrep` |
| `grep` | `bin/grep` |

## Download

The package file (`grep-3.11.tpkg`) and the sources it was built from are the assets of the
[v3.11 release](https://github.com/Artfical/tpkg-grep/releases/tag/v3.11).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `grep-3.11.tar.xz`

Check a download: `sha256sum grep-3.11.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
