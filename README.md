# pdfoverlay — A LaTeX style for overlaying text on a PDF

The `pdfoverlay` package provides a simple interface to overlay text on to an
existing PDF. The text to be overlayed is typeset and positioned normally as
you would any other LaTeX document. Some or all of the pages of the PDF can be
included and not all pages of the PDF need have overlayed text. It’s also
possible to include text between pages of the PDF.

## Installation from TeXLive or MiKTeX

`pdfoverlay` is in TeXLive and MiKTeX and can be installed in the usual way
through your distribution. e.g., in TeXLive by running:

```
tlmgr install pdfoverlay
```

## Installation from CTAN

Download and unpack `pdfoverlay.zip` from CTAN at
https://ctan.org/pkg/pdfoverlay

Change to the `pdfoverlay` directory, then run:

```
tex pdfoverlay.ins
```

to generate `pdfoverlay.sty`.

Copy `pdfoverlay.sty` to `$TEXMFHOME/tex/latex/pdfoverlay/` and `pdfoverlay.pdf` to `$TEXMFHOME/doc/latex/pdfoverlay/`.

You can find `$TEXMFHOME` by running:

```
kpsewhich -var-value=TEXMFHOME
```

## Installation from Git Source

`pdfoverlay` uses the `l3build` system.

Clone the git repository using:

```
git clone https://github.com/dcpurton/pdfoverlay.git
```

Change to the `pdfoverlay` directory, and then the style file
(`pdfoverlay.sty`) and documentation (`pdfoverlay.pdf`) can be installed by
running:

```
l3build install --full
```

## Licence

```
Copyright (c) 2018-2019 David Purton <dcpurton@marshwiggle.net>

This work may be distributed and/or modified under the conditions of
the LaTeX Project2 Public License, either version 1.3c of this license
or (at your option) any later version. The latest version of this
license is in
   http://www.latex-project.org/lppl.txt
and version 1.3c or later is part of all distributions of LaTeX
version 2005/12/01 or later.

This work is "maintained" (as per the LPPL maintenance status)
by David Purton.

This work consists of the files pdfoverlay.ins, pdfoverlay.dtx, README.md,
and the derived files pdfoverlay.sty and pdfoverlay.pdf
```
