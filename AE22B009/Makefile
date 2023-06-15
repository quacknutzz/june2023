#This is the makefile for the pdfLaTeX

#Use the command `make all` to compile all the tex files and result in a PDF finally.

all: ae22b009.tex Image.png bibliography.bib
	pdflatex ae22b009
	bibtex ae22b009
	pdflatex ae22b009
	pdflatex ae22b009

#Everything under the label `all`, that is the commands under the label get executed.

#Use `make clean` to remove all the temp files.

clean:
	rm -f ae22b009.aux ae22b009.bbl ae22b009.blg ae22b009.log ae22b009.out

