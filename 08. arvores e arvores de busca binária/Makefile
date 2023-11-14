all:
	#pandoc -s topico8.md -o topico8.tex -V geometry:margin=1in -V colorlinks --template=/home/juliano/.pandoc/default.latex
	pandoc -s topico8.md -o topico8.tex -V geometry:margin=1in -V colorlinks -V documentclass=article -V papersize=a4
	pdflatex topico8.tex
	rm *.out *.log
