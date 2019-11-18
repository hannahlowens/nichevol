nichevol: An R package for assessment of evolutionary change of
ecological niches
================
Marlon E. Cobos, Hannah Owens, and A. Townsend Peterson

  - [Package description](#package-description)
  - [Installing the package](#installing-the-package)
  - [Exploring the nichevol package](#exploring-the-nichevol-package)
      - [Setting a directory](#setting-a-directory)
      - [Functions in nichevol](#functions-in-nichevol)

<br>

## Package description

The **nichevol** R package helps to perform critical steps of the
process of assessment of evolution of species ecological niches. The
main analyses include: initial exploration of environmental data in
species records and accessible areas, preparation of data for
phylogenetic analyses, phylogenetic analyses, and plotting for
interpretations.

<br>

## Installing the package

**nichevol** is in a GitHub repository and can be installed and/or
loaded using the code below (make sure to have Internet connection).

Note: Try the code below first… If you have any problem during the
installation, restart your R session, close other sessions you may have
open, and try again. If during the installation you are asked to update
packages, please do it (select the option that says All). If any of the
packages gives an error, please install it alone using
install.packages(), then try re-installing **nichevol** again. Also, it
may be a good idea to update R and RStudio (if you are using it).

``` r
# Installing and loading packages
if(!require(devtools)){
    install.packages("devtools")
}
if(!require(nichevol)){
    devtools::install_github("marlonecobos/nichevol")
}
library(nichevol)
```

<br>

## Exploring the nichevol package

### Setting a directory

The main functions of the **nichevol** package produce results that need
to be written in a directory in your computer. Writing the results
outside the R environment helps to avoid problems related to RAM
limitations. That is why, setting a working directory is recommended
before starting. You ca do that using the code below:

``` r
setwd("Drive:/Your/Directory") # change the characters accordingly
```

<br>

### Functions in nichevol

A complete list of the main functions in the **nichevol** package can be
found in the package documentation. Use the following code to see the
list.

``` r
help(nichevol)
```
