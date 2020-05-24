menu:
	python ./jemdoc.py -c custom.conf -o ../ index.jemdoc

bio:
	python ./jemdoc.py -o ../ biography.jemdoc

news:
	python ./jemdoc.py -o ../ news.jemdoc

teaching:
	python ./jemdoc.py -o ../ teaching.jemdoc

services:
	python ./jemdoc.py -o ../ services.jemdoc

awards:
	python ./jemdoc.py -o ../ awards.jemdoc

contact:
	python ./jemdoc.py -o ../ contact.jemdoc

hightlight:
	python ../ref/bibconvert.py --suffix web --highlight "Y. Li" --highlight "Yongfu Li" --highlight "Li, Yongfu" --input ../ref/Top.bib --input ../ref/publications.bib --header publications_header.jemdoc > publications.jemdoc

publications:
	python ./jemdoc.py  -o ../ publications.jemdoc

all: menu bio news teaching services awards contact hightlight
