t=jmir
all: compile run
	
compile:
	pdflatex ${t}.tex

abstract:
	pdflatex sigir2016_abstract.tex

allan:
	pdflatex sigir2016_allan.tex

bib:
	bibtex ${t}

run:
	evince ${t}.pdf &

clean:
	rm -f ${t}.dvi ${t}.log ${t}.aux ${t}.bbl ${t}.blg

