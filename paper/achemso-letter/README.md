To compile, you will need to have LaTeX installed on your machine:
```
sudo apt update
sudo apt install texlive-latex-extra
```

After installation, run the following commands to compile:
```
pdflatex main.tex
bibtex main.aux
pdflatex main.tex
pdflatex main.tex
```
or simply run the `make` command.

Finally, you can open the compiled PDF using:
```
open main.pdf
```