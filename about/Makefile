
cvtex = CV_tournier.tex
outdir = .

pdf: $(cvtex)
	pdflatex -output-directory $(outdir) $<

clean:
	-rm *.log
	-rm *.aux
	-rm *.out
