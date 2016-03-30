# workflow

Bestanden die nodig zijn voor het produceren van fatsoenlijke papers.

In navolging van [plain-text.co](http://plain-text.co) is het hele process is geautomatiseerd m.b.v. make en pandoc. `pandoc` bevat de essentiele bestanden uit `~/.pandoc`, i.e. templates, een csl-bestand en een citeproc-template.

## now with iPad support

Using a bash script, a small server, a markdown app and an ssh app (and Dropbox) I can now ssh into my home computer using my iPad, create a new project including a markdown template and a git repo, sync it all with Dropbox (if it's in my university folder), and write a paper on my iPad using the markdown app's Dropbox integration (why would anyone want to do that?!).

## Requirements

- [pandoc](http://pandoc.org/README.html)
- [pandoc-crossref](https://github.com/lierdakil/pandoc-crossref)
- pandoc-citeproc 
- [GNU make](https://www.gnu.org/software/make/)

## To do:

[] finish this readme
[] make a beamer template



