# economics-and-business-administration
LaTeX file related to "Economia e gestione aziendale" course in UNIFE 
(University of Ferrara), year 2014-2016.

## What this repository is about
This repository consists in a business plan presentation in Italian language 
concerning a fictional enterprise.

The presentation is written in LaTeX using the beamer class.

## How to compile and compress the resulting pdf file
```
$ pdflatex business_plan.tex
$ gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dNOPAUSE -dQUIET -dBATCH 
-sOutputFile=compressedFile.pdf business_plan.pdf

```

## License
Do What The Fuck You Want To Public License, Version 2.
