## robackdata

R package containing the data provided in *Beyond Multiple Linear Regression* by Roback and Legler.

All the data in this package was taken from here:

<https://github.com/proback/BeyondMLR>

The online version of the textbook can be found here:

<https://bookdown.org/roback/bookdown-BeyondMLR/>


To install this package, run the following R code:

```r
# first install the 'remotes' package if you don't have it already
install.packages("remotes")
remotes::install_github("dfriend21/robackdata")
```

All data sets referenced in the textbook are contained in this package. The name of a dataset is the name of the file referenced in the book without the file extension (.csv). For example, to access the Kentucky Derby dataset used in Chapter 1 ([derbyplus.csv](https://github.com/proback/BeyondMLR/blob/master/data/derbyplus.csv)), you can run the following R code:

```r
dp <- robackdata::derbyplus
```

Roback, Paul, and Julie Legler. *Beyond multiple linear regression: applied generalized linear models and multilevel models in R*. Chapman and Hall/CRC, 2021.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.