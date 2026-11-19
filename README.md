![openfluids.github.io banner](https://raw.githubusercontent.com/openfluids/openfluids.github.io/main/assets/readme-banner-v3.jpg)

[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](LICENSE)

`openfluids.github.io` is the openfluids website: an open, collaborative workshop for fluid flows.

The page is built by the machine-made site generator
([machine-made/machine-made.github.io](https://github.com/machine-made/machine-made.github.io)),
the same code, look and tab row as every house. This repository holds the built site in `docs/`.

## Change the site

The content lives in the generator repository, `houses/openfluids/site.json`, with its public list in
`houses/openfluids/allow.json`. Build it into this repository and open a pull request:

```
sh publish.sh openfluids ../openfluids.github.io
```

Do not edit `docs/` by hand. GitHub Pages serves `main`, folder `/docs`.

## Licence

Apache-2.0. See [LICENSE](LICENSE). The fonts in `docs/fonts/` stay under the SIL Open Font License 1.1. See `docs/fonts/mm-sans-OFL.txt` and `docs/fonts/mm-weft-OFL.txt`.
