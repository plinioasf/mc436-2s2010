file=diagCase
file2=diagCase
file3=login
make:
	latex $(file3).tex
	latex $(file3).tex
	dvips $(file3).dvi -o
	ps2pdf13  $(file3).ps
show:
	evince $(file).pdf
clean:
	rm *.dvi *.aux *.out *.log
mind:
	pdflatex $(file2).tex
den:
	pdflatex desenho.tex

