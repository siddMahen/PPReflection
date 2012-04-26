
DOC=doc

build:
	latex $(DOC)
	bibtex $(DOC)
	latex $(DOC)
	pdflatex $(DOC)

render: build
	open -a Preview $(DOC).pdf
