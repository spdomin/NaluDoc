#
#  Type 'make all' to build the whole thing.
#  Type 'make clean' to before checkin.
#

SRC = adaptivity.tex advectionStabilization.tex boundaryConditions.tex couplingApproach.tex discretizationApproach.tex \
lowMachNumberDerivation.tex pressureStabilization.tex propertyEvaluation.tex rteStabilization.tex supportedEquationSet.tex \
timeDiscretization.tex topologicalSupport.tex turbulenceModeling.tex

all:
	rm -rf *.aux
	pdflatex naluLowMachTheory 
	bibtex naluLowMachTheory 
	pdflatex naluLowMachTheory
	pdflatex naluLowMachTheory

clean:
	-rm -f *.aux *.log *.dvi *.bbl *.blg *.toc *.lof *.lot *.out
