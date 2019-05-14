# Simple Makefile to compile the document. Produces t1spec.pdf.
#
# On Ubuntu 18.04, the following packages _should_ be sufficient:
#   texlive-latex-base
#   texlive-latex-recommended
#   texlive-latex-extra
#   texlive-fonts-recommended
#   texlive-fonts-extra

.POSIX:

SRC = compiler.tex functions.tex interpreter.tex lexer.tex t1spec.tex overview.tex names.tex types.tex

t1spec.pdf: $(SRC)
	pdflatex t1spec.tex
	pdflatex t1spec.tex

clean:
	-rm -f t1spec.pdf t1spec.aux t1spec.log t1spec.out t1spec.toc
