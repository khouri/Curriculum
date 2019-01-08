FILE = Curriculum_Adilson_Khouri

all :
	echo "Compilando"
	pdflatex $(FILE).tex
	evince $(FILE).pdf
	rm *.bbl *.blg *.aux *log *.brf *.out

clean:
	echo "Limpando arquivos auxiliares"
	rm *.bbl *.blg *.aux *log *.brf *.out
