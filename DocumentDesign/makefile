TARGET=DesignDocument
HTML=main_html
SRC={DesignDocument}

default: all 

all:
	latex DesignDocument.tex
	dvips -R -Poutline -t letter DesignDocument.dvi -o DesignDocument.ps
	ps2pdf DesignDocument.ps
	rm DesignDocument.aux
	rm DesignDocument.dvi
	rm DesignDocument.log
	rm DesignDocument.ps
	rm DesignDocument.out
	rm DesignDocument.toc