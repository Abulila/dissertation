all:
	pdflatex thesis
	bibtex -min-crossrefs=1000 thesis
	pdflatex thesis
	pdflatex thesis

clean:
	${RM} *~ *.aux *.log *.dvi *.ps *.pdf body.tmp head.tmp *.bbl *.blg *.toc *.lof
