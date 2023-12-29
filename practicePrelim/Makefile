include make.inc
default: prelimAnswers.pdf prelim.pdf

prelim.pdf: prelim.tex
	$(LC) prelim.tex
	$(LC) prelim.tex

prelimAnswers.pdf: prelim.tex
	$(LC) "\def\isanswers{1} \input{prelim.tex}"
	$(LC) "\def\isanswers{1} \input{prelim.tex}"
	mv prelim.pdf prelimAnswers.pdf

clean: 
	rm prelimAnswers.pdf prelim.pdf
