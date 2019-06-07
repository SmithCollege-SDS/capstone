#!/usr/bin/env Rscript

all: www

www: index.Rmd  _site.yml include/after_body.html include/smith.css index.Rmd sponsors.Rmd
	Rscript -e "rmarkdown::render_site();"

clean:
	Rscript -e "rmarkdown::clean_site();"