# makefile for tex to pdf convertion

FILENAME = ch22b008

$(FILENAME).pdf: $(FILENAME).tex
	pdflatex $(FILENAME).tex
	rm $(FILENAME).aux $(FILENAME).log $(FILENAME).out

PDF: $(FILENAME).pdf
	xpdf $(FILENAME).pdf

