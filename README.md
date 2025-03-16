# Description
tex3pdf is an expansion on a bash script I used to make pdf documents from tex. It uses pdflatex and bibtex

It should be placed or symlinked with `$PATH`, for eg. on my system it's in `~/.local/bin/` for ease of use.

# Use
```
tex3pdf [options] [-f FILENAME] [-o OUTPUT]
-h      get this help
-f      specify input tex file, default is main.tex
-o      specify output pdf file, default is document.pdf
-b      use when you tex file includes references from a bib file
```
