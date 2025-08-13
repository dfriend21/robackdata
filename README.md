## robackdata

R package containing the data provided in Beyond Multiple Linear Regression by Roback and Legler.

All the data in this package was taken from here:

<https://github.com/proback/BeyondMLR>

The online version of the textbook can be found here:

<https://bookdown.org/roback/bookdown-BeyondMLR/>


To install this package

All data sets referenced in the textbook are contained in this package. The name of a dataset is the name of the file referenced in the book without the file extension (.csv). For example, to access the Kentucky Derby dataset used in Chapter 1 ([derbyplus.csv](https://github.com/proback/BeyondMLR/blob/master/data/derbyplus.csv)), you can run the following R code:

```r
dp <- robackdata::derbyplus
```

Roback, Paul, and Julie Legler. *Beyond multiple linear regression: applied generalized linear models and multilevel models in R*. Chapman and Hall/CRC, 2021.