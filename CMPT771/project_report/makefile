all:
	latex paper.tex
	bibtex paper.aux
	latex paper.tex
	latex paper.tex
	dvipdf paper.dvi
	rm paper.blg paper.log paper.aux paper.bbl paper.dvi 
	evince paper.pdf &
	
clean:
	rm paper.blg paper.log paper.aux paper.bbl paper.dvi
	
