TARGET=ProgressReport
HTML=main_html
SRC={ProgressReport}

default: all 

all:
	latex ProgressReport.tex
	dvips -R -Poutline -t letter ProgressReport.dvi -o ProgressReport.ps
	ps2pdf ProgressReport.ps
	rm ProgressReport.aux
	rm ProgressReport.dvi
	rm ProgressReport.log
	rm ProgressReport.ps
	rm ProgressReport.toc