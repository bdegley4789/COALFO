TARGET=Requirements
HTML=main_html
SRC={Requirements}

default: all 

all:
	latex Requirements.tex
	dvips -R -Poutline -t letter Requirements.dvi -o Requirements.ps
	ps2pdf Requirements.ps
	rm Requirements.aux
	rm Requirements.dvi
	rm Requirements.log
	rm Requirements.ps