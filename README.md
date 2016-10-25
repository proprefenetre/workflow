# basic workflow

it works like this: 

Markdown -> Pandoc -> Latex -> PDF -> master's degree

## requirements

- [pandoc-citeproc](https://hackage.haskell.org/package/pandoc-citeproc)
- [pandoc-citeproc-preamble](https://github.com/spwhitton/pandoc-citeproc-preamble)
- [pandoc-crossref](https://github.com/lierdakil/pandoc-crossref)

## files

The `pandoc` directory contains the (latex) templates, csl specifications and
citeproc-preamble that I use. I generally symlink it to ~/.pandoc.

## scripts

`bin` contains some scripts that I use to make my life easier. I cannot vouch
for their quality or actual usefulness.
