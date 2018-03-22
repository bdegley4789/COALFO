TARGET=AlphaRelease
HTML=main_html
SRC={AlphaRelease}

default: all 

all:
	latex AlphaRelease.tex
	dvips -R -Poutline -t letter AlphaRelease.dvi -o AlphaRelease.ps
	ps2pdf AlphaRelease.ps
	rm AlphaRelease.aux
	rm AlphaRelease.dvi
	rm AlphaRelease.log
	rm AlphaRelease.ps
	rm AlphaRelease.out