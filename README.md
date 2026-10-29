# openfluids.github.io

The openfluids website: open tools for fluid flows. A machine-made house.

The page is built by the machine-made site generator
([machine-made/machine-made.github.io](https://github.com/machine-made/machine-made.github.io)),
the same code, look and tab row as every house. This repository holds the built site in `docs/`.

## Change the site

The content lives in the generator repository, `houses/openfluids/site.json`, with its public list
in `houses/openfluids/allow.json`. Build it into this repository and open a pull request:

```
sh publish.sh openfluids ../openfluids.github.io
```

Do not edit `docs/` by hand.

## Status

Built. Goes live when the founder makes this repository public and turns on GitHub Pages (source:
`main`, folder `/docs`).
