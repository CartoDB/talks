.PHONY: clean

index.html:
	jupyter nbconvert cli-workshop.ipynb --to html 
	mv cli-workshop.html index.html

clean:
	rm index.html
