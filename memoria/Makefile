latex: dissertation_main.tex chap1/bibliografia.bib chap1/introduccion.tex
	pdflatex -shell-escape dissertation_main
	bibtex dissertation_main
	pdflatex -shell-escape dissertation_main

clean:
	rm -r *~ _*  *.aux  *.bcf *.lof *.lot *.xml *.log *.out *.toc *.bbl *.blg *.dvi *-blx.bib *.fls *.fdb_latexmk
  

