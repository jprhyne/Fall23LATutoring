include make.inc
default: prelimBin3Answers.pdf prelimBin3.pdf

prelimBin3.pdf: prelimBin3.tex
	$(LC) prelimBin3.tex
	$(LC) prelimBin3.tex

prelimBin3Answers.pdf: prelimBin3.tex
	$(LC) "\def\isanswers{1} \input{prelimBin3.tex}"
	$(LC) "\def\isanswers{1} \input{prelimBin3.tex}"
	mv prelimBin3.pdf prelimBin3Answers.pdf

clean: 
	rm prelimBin3Answers.pdf prelimBin3.pdf
