## Prerequisites

Нужен дистрибутив TeX:
* Для ОС Windows - TeX Live

## Резюме в формате LaTeX
Для генерации PDF:
```
$ pdflatex ./cv-ru.tex
$ pdflatex ./cv-en.tex
```
Могут понадобиться шрифты:<br />
```
# apt install texlive-fonts-extra
``` 

## TODO
GitHub Actions, чтобы сам PDF собирал.
