include make.inc
default: prelimBin4Answers.pdf prelimBin4.pdf

prelimBin4.pdf: prelimBin4.tex
	$(LC) prelimBin4.tex
	$(LC) prelimBin4.tex

prelimBin4Answers.pdf: prelimBin4.tex
	$(LC) "\def\isanswers{1} \input{prelimBin4.tex}"
	$(LC) "\def\isanswers{1} \input{prelimBin4.tex}"
	mv prelimBin4.pdf prelimBin4Answers.pdf

clean: 
	rm prelimBin4Answers.pdf prelimBin4.pdf
