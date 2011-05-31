all: clean
	# WARNING: We need bibtex and the cite package.
	# on Ubuntu: apt-get install texlive-latex-recommended
	pdflatex gruppe4.tex
	bibtex gruppe4
	pdflatex gruppe4.tex
	pdflatex gruppe4.tex

clean:
	rm -f gruppe4.pdf *.aux gruppe4.log *.log gruppe4.toc *.out *.bbl *.blg
