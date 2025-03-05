# Duke CEI Presentation Template w/ Beamer

Here is the Duke CEI template that I use to create presentations with LaTeX's
beamer package. [The `update.tex`](update.tex) file is the presentation file
that should be edited. [The `preamble.tex`](preamble.tex) file contains the
title page and imports various latex packages that are commonly used.

## Directory structure for Multiple Presentations
If you are creating multiple presentations I find it convenient to use the
following structure,
```
presentations/
| preamble.tex
| update.bib
| images/
| | ...
| presentation1/
| | update.tex
| | ...
| | update.pdf
```
and edit the `update.tex` to utilize the correct images dir, bib file, and
preamble.

## Viewing
I prefer to view informal presentations with
[Zathura](https://pwmt.org/projects/zathura/) for its minimalist interface and
efficient navigation. If you would like a presenter view similar to Powerpoint,
I like to use [pdfpc](https://pdfpc.github.io/). You can view a beamer pdf with
notes in pdfpc using the `-n bottom` option. See the pdfpc
[guide](https://github.com/pdfpc/pdfpc/releases/latest/download/pdfpc-demo.pdf)
for a description of all the pdfpc features.
