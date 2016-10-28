all: clean default

default:
	latex prop.tex
	latex prop.tex
	bibtex prop
	latex prop.tex
    
clean:
	-rm *.aux
	-rm *.log
	-rm *.bbl
	-rm *.dvi
	-rm *.out
	-rm *.blg

cleanall: clean
	-rm *.pdf
