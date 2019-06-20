PDFLATEX = pdflatex -shell-escape -interaction=nonstopmode -file-line-error

CLI = cli_cheats_sheet

all: $(CLI).pdf clean

$(CLI).pdf: $(CLI).tex
	$(PDFLATEX) $(CLI).tex

clean :
	rm -f $(CLI).log $(CLI).aux $(CLI).blg $(CLI).toc
