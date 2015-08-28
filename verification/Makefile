#
#  Type 'make all' to build the whole thing.
#  Type 'make clean' to before checkin.
#

SRC = verification.tex

all:
	rm -rf *.aux
	/usr/bin/pdflatex naluLowMachVerification 
	/usr/bin/bibtex naluLowMachVerification 
	/usr/bin/pdflatex naluLowMachVerification

clean:
	-rm -f *.aux *.log *.dvi *.bbl *.blg *.toc *.lof *.lot *.out
