main.pdf: main.tex references.bib
	pdflatex main
	bibtex main
	pdflatex main
	pdflatex main

clean:
	@rm -f main.aux main.bbl main.blg main.log main.out main.spl

cleanall:
	@rm -f main.aux main.bbl main.blg main.log main.out main.spl main.pdf
