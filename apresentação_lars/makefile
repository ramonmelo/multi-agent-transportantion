# Execute with 'make -i'

all: compile clean
compile:
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex
	mv main.pdf README.pdf
clean:
	rm *.aux *.bbl *.log *.loa *.blg *.los *.out *.lot *.lof *.toc *.tdo
