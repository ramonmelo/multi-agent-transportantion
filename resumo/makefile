# Execute with 'make -i'

all: compile clean
compile:
	pdflatex sbc-template.tex
	bibtex sbc-template
	pdflatex sbc-template.tex
	pdflatex sbc-template.tex
	mv sbc-template.pdf README.pdf
clean:
	rm *.aux *.bbl *.log *.loa *.blg *.los *.out *.lot *.lof *.toc *.tdo
