compile:
	xelatex Tomasz_Kulik.tex

show:
	evince Tomasz_Kulik.pdf

clean:
	find . -regex '.*\.\(aux\|bbl\|log\|blg\|toc\|out\|snm\|nav\|o\|xml\|bcf\|synctex.gz\)' -delete

full:
	make compile && make clean && make show
