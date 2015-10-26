all: index.html install.html resources.html vimrc.html

index.html: index.md
	pandoc index.md -o index.html -c buttondown.css

install.html: install.md
	pandoc install.md -o install.html -c buttondown.css

resources.html: resources.md
	pandoc resources.md -o resources.html -c buttondown.css

vimrc.html: vimrc.md
	pandoc vimrc.md -o vimrc.html -c buttondown.css

.PHONY: all clean
clean:
	rm -f *.html
