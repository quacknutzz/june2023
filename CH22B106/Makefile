all: ch22b106.pdf 

ch22b106.pdf: ch22b106.tex
	pdflatex ch22b106.tex
	bibtex ch22b106
	pdflatex ch22b106.tex
	pdflatex ch22b106.tex

clean: 
	rm -f ch22b106.aux ch22b106.bbl ch22b106.log ch22b106.blg
