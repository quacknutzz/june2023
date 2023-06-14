all : ch22b098.pdf

ch22b098.pdf : ch22b098.tex
	pdflatex ch22b098
	bibtex ch22b098
	pdflatex ch22b098
	pdflatex ch22b098
	
	

clean: 
	-rm ch22b098.aux ch22b098.bbl ch22b098.blg ch22b098.log
