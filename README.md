# r-header

Here is the header I like to add to my standalone R scripts (i.e. not scripts that contain functions as part of a package).

```{r}
## ---------------------------
##
## Script name: 
##
## Purpose of script:
##
## How to use:
##
## Author: Raphael Scherrer
##
## Date Created: `r paste(Sys.Date())`
##
## This script comes with no guarantee whatsoever.
##
## Copyright (c) Raphael Scherrer, `r paste(format(Sys.Date(), "%Y"))`
##
## Find me on GitHub at https://github.com/rscherrer
##
## Email: 
## r.scherrer@rug.nl
## raphael.scherrer@evobio.eu
## raph.rjfs@hotmail.fr
##
## ---------------------------
``` 

A header can be automatically added to a script in RStudio by using [snippets](https://support.rstudio.com/hc/en-us/articles/204463668-Code-Snippets).

This was inspired by stumbling upon Tim Farewell's [website](https://timfarewell.co.uk/my-r-script-header-template/).
