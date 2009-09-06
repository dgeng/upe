TEX = upe.tex preface.tex \
	ch1.tex ch2.tex ch3.tex ch4.tex ch5.tex ch6.tex ch7.tex ch8.tex ch9.tex

all: upe.pdf

upe.pdf: ${TEX}
	pdflatex upe.tex
	pdflatex upe.tex

clean:
	rm upe.pdf *.toc *.log *.aux *.out

