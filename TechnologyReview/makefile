TARGET=TechnologyReview
HTML=main_html
SRC={TechnologyReview}

default: all 

all:
	latex TechnologyReview.tex
	dvips -R -Poutline -t letter TechnologyReview.dvi -o TechnologyReview.ps
	ps2pdf TechnologyReview.ps
	rm TechnologyReview.aux
	rm TechnologyReview.dvi
	rm TechnologyReview.log
	rm TechnologyReview.ps
	rm TechnologyReview.out