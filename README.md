# tex2img2
Script to convert each page of a tex file to an image (pdf, eps, svg, png) using the latex standalone package.

## Requirements:

### Latex package(s):
standalone package.

### pdf image: 
(pdflatex) or (latex, dvipdf) or (latex, dvips, ps2pdf) or (xelatex)
pdfinfo, gs

### png image: 
(latex, dvipng) or (pdflatex, pdfinfo, gs, imagemagick)

### svg image: 
(latex, dvisvgm) or (pdflatex, pdfinfo, gs, pdf2svg)

### eps image: 
(pdflatex, pdfinfo, gs, pdftops)

Also see:
https://github.com/asarkar2/tex2img
