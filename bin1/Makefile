include make.inc
default: prelimBin1Answers.pdf prelimBin1.pdf

prelimBin1.pdf: prelimBin1.tex
	$(LC) prelimBin1.tex
	$(LC) prelimBin1.tex

prelimBin1Answers.pdf: prelimBin1.tex
	$(LC) "\def\isanswers{1} \input{prelimBin1.tex}"
	$(LC) "\def\isanswers{1} \input{prelimBin1.tex}"
	mv prelimBin1.pdf prelimBin1Answers.pdf

clean: 
	rm prelimBin1Answers.pdf prelimBin1.pdf
