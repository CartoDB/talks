.PHONY: clean

index.html:
	jupyter nbconvert cli-workshop.ipynb --to slides --SlidesExporter.reveal_theme=default --SlidesExporter.reveal_scroll=True --reveal-prefix="../resources/reveal.js/reveal.js-3.5.0"
	mv cli-workshop.slides.html index.html

clean:
	rm index.html
