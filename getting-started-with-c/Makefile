.PHONY: all clean

all: Tutorial.html

%.html: %.asciidoc
	asciidoctor Tutorial.asciidoc

clean:
	rm -f *.html
