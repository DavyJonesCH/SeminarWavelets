#
# Makefile -- build images for chapter 3
#
# (c) 2019 Prof Dr Andreas Müller, Hochschule Rapperswil
#
all:	stueckweise1.pdf	\
	stueckweise8.pdf	\
	stueckweise64.pdf	\
	wavelets.pdf		\
	haar-vater.pdf
	
stueckweise1.pdf:	stueckweise1.tex stueckcommon.tex
	pdflatex stueckweise1.tex
	
stueckweise8.pdf:	stueckweise8.tex stueckcommon.tex
	pdflatex stueckweise8.tex

stueckweise64.pdf:	stueckweise64.tex stueckcommon.tex
	pdflatex stueckweise64.tex

wavelets.pdf:	wavelets.tex
	pdflatex wavelets.tex

haar-vater.pdf:	haar-vater.tex
	pdflatex haar-vater.tex
