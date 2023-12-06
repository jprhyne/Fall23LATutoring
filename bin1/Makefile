default: prelimBin1Answers.pdf prelimBin1.pdf

prelimBin1.pdf: prelimBin1.tex
	pdflatex prelimBin1.tex

prelimBin1Answers.pdf: prelimBin1.tex
	pdflatex "\def\isanswers{1} \input{prelimBin1.tex}"
	mv prelimBin1.pdf prelimBin1Answers.pdf
