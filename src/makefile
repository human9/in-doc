# pdflatex makefile
#

text.pdf: docs.tex
	latexmk -pdf -outdir=../target docs
#	pdflatex -output-directory=../target docs.tex

open: text.pdf
	evince ../target/docs.pdf


clean:
	rm ../target/*
