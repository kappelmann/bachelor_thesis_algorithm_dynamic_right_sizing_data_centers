BUILD_DIR=build
TARGET=Algorithms_Right-Sizing_Data_Centers_Kappelmann

.PHONY: all clean watch

OPTIONS=-bibtex -pdf -pdflatex="pdflatex --shell-escape"

all:
	latexmk $(OPTIONS) $(TARGET).tex
force:
	latexmk -gg $(OPTIONS) $(TARGET).tex
watch:
	latexmk -pvc $(OPTIONS) $(TARGET).tex
clean:
	rm -rf *.aux *.bbl *.blg *.fdb_latexmk *.fls *.lof *.log *.lot *.out *.gnuplot *.table *.toc
