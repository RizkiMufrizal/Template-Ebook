Template-Ebook
==============

cara Menjalankan:

```
pandoc --template template-latex.tex --variable mainfont="Droid Serif" --variable sansfont="Droid Sans" --variable fontsize=12pt --variable version=1.0 --latex-engine=xelatex --toc -N -V documentclass=report -o output.pdf 00-cover.md 01-pendahuluan.md 02-penggunaan.md 03-sintak.md
```
