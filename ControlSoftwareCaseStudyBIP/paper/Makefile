main.pdf: main.tex *.tex main.bib
	pdflatex main
	bibtex main
	pdflatex main
	pdflatex main

clean:
	rm -f *.aux *.bbl *.blg *.log *.toc *.dvi *.gx.table *.gx.gnuplot main.ps main.pdf main.fdb_latexmk main.fls main.tdo *~

