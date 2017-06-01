index.html: index.adoc
	asciidoc -b html5 -a icons -a toc2 -a theme=flask index.adoc

index.adoc: index.org
	pandoc --columns=100 -f org -t asciidoc -s index.org -o index.adoc
