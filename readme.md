## About ##
Scaling Viki is a free book detailing the redesign of Viki.com's platform.

The book was written by [Karl Seguin](http://openmymind.net), with co-creator [Cristobal Viedma](https://twitter.com/viedma)'s assistance.

If you liked this book, maybe you'll also like my [The Little Redis Book](http://openmymind.net/2012/1/23/The-Little-Redis-Book/) or [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/).

## License ##
The book is freely distributed under the [Attribution-NonCommercial 3.0 Unported license](<http://creativecommons.org/licenses/by-nc/3.0/legalcode>).

## Formats ##
The book is written in [Markdown](http://daringfireball.net/projects/markdown/) and converted to PDF using [Pandoc](http://johnmacfarlane.net/pandoc/).

The TeX template makes use of [Lena Herrmann's JavaScript highlighter](http://lenaherrmann.net/2010/05/20/javascript-syntax-highlighting-in-the-latex-listings-package).

Kindle and ePub format provided using [Pandoc](http://johnmacfarlane.net/pandoc/).

## Generating books ##
Packages listed below are for Ubuntu. If you use another OS or distribution names would be similar.

### PDF

#### Dependencies

Packages:

* `pandoc`
* `texlive-xetex`
* `texlive-latex-extra`
* `texlive-latex-recommended`

You should have Microsoft fonts installed too. But you could change fonts in `common/pdf-template.tex` file if you want.

#### Building

Run `make en/scaling-viki.pdf`.

### ePub

#### Dependencies

Packages:

* `pandoc`

#### Building

Run `make en/scaling-viki.epub`.

### Mobi

#### Dependencies

Packages:

* `pandoc`

You should have [KindleGen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211) installed too.

#### Building

Run `make en/scaling-viki.mobi`.

## Title Image ##
A PSD of the title image is included. The font used is [Comfortaa](http://www.dafont.com/comfortaa.font).
