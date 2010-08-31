file=requesitos
file2=mindmap
make:
	latex $(file).tex
	latex $(file).tex
	dvips $(file).dvi -o
	ps2pdf13 -sPAPERSIZE=a4 $(file).ps
show:
	evince $(file).pdf
clean:
	rm *.dvi *.aux *.out *.log
mind:
	pdflatex $(file2).tex
den:
	pdflatex desenho.tex

