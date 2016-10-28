all: clean default

default:
	pdflatex prop.tex
	pdflatex prop.tex
	bibtex prop
	pdflatex prop.tex
	pdflatex prop.tex
    
clean:
	-rm *.aux
	-rm *.log
	-rm *.bbl
	-rm *.out
	-rm *.blg

cleanall: clean
	-rm *.pdf
