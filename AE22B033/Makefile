TEXFILE = AE22B033.tex
PDF = $(TEXFILE:.tex=.pdf)

.PHONY: all clean

all: $(PDF)

$(PDF): $(TEXFILE)
	pdflatex $(TEXFILE)

clean:
	rm -f *.aux *.log *.pdf

