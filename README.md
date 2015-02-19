cv-template
===========

Сurriculum vitæ / Résumé template

This CV template relies on the use of [pandoc](http://johnmacfarlane.net/pandoc/)
to deliver CV in multiple formats.

### Using LaTeX template

To build CV in a PDF format using LaTeX template run this command:

```
$ pandoc --template cv.tex -o cv.pdf cv.md
```

The result should look like [this](output/cv.pdf):

![Sample LaTeX PDF output.](output/latex-pdf.png)

