include make.inc
default: prelimBin2Answers.pdf prelimBin2.pdf

prelimBin2.pdf: prelimBin2.tex
	$(LC) prelimBin2.tex
	$(LC) prelimBin2.tex

prelimBin2Answers.pdf: prelimBin2.tex
	$(LC) "\def\isanswers{1} \input{prelimBin2.tex}"
	$(LC) "\def\isanswers{1} \input{prelimBin2.tex}"
	mv prelimBin2.pdf prelimBin2Answers.pdf

clean: 
	rm prelimBin2Answers.pdf prelimBin2.pdf
