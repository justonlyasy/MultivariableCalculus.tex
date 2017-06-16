# MultivariableCalculus.tex

This repository contains source code for a multivariable calculus text used as a part of *Interphase*, a summer program for entering freshmen at MIT.

To compile, you need pdfLaTeX and Asymptote (both of which are included in standard TeX installations). To compile, run: 

```
pdflatex MultivariableCalculus.tex
cd asy
asy *-*.asy
cd ../
pdflatex MultivariableCalculus.tex
pdflatex MultivariableCalculus.tex
pdflatex MultivariableCalculus.tex
```