SRC := $(wildcard *.dot *.eps)
OUT := $(SRC:.dot=.eps) $(SRC:.dot=.pdf) $(SRC:.eps=.pdf)
all: ${OUT}

.dot.eps: *.dot
	dot -Tps -o $@ $<
.eps.pdf: *.eps
	epstopdf $<

.SUFFIXES: .pdf .eps .dot .dvi .tex .ps
