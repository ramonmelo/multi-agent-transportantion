# Execute with 'make -i'

all: compile clean
compile:
	pdflatex main.tex
	bibtex main
	makeglossaries main
	pdflatex main.tex
	pdflatex main.tex
	mv main.pdf README.pdf
clean:
	rm *.aux *.bbl *.log *.loa *.blg *.los *.out *.lot *.lof *.toc *.tdo *.acn *.acr *.alg *.glg *.glo *.gls *.glsdefs *.ist *.sbl *.slg *.sym *.tdn *.tld *.tlg *.defs *.acro *.symb *.symbh *.sb1 *.sb2 *.sb3 *.sb4
