# Purpose

The R package 'MaxentVariableSelection' helps selecting the most
important set of uncorrelated environmental variables along with the
optimal regularization multiplier for Maxent Niche Modeling. This
allows constrain model complexity, and thus, to increase model
peformance and transferability of habitat suitability to novel
environmental conditions (e.g. future climate scenarios).

# Installation

To install and load the package from CRAN, type:

```{r, eval=FALSE}
install.packages("DEMEtics")
library(DEMEtics)
```

To install and load the package from github, type:

```{r, eval=FALSE}
install.packages("devtools") 
devtools::install_github("alj1983/DEMEtics")
library(DEMEtics)
```
# Documentation

The folder 'vignettes' contains documentation files that show how to
use the package. The main function of the package
(*VariableSelection*) and the example datasets in 'inst/extdata' are
described in the 'MaxentVariableSelection-manual.pdf'.

