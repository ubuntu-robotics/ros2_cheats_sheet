PDFLATEX = pdflatex -shell-escape -interaction=nonstopmode -file-line-error

MAIN = colcon_cheats_sheet

all: $(MAIN).pdf clean

$(MAIN).pdf: $(MAIN).tex
	$(PDFLATEX) $(MAIN).tex

clean :
	rm -f $(MAIN).log $(MAIN).aux $(MAIN).blg $(MAIN).toc
