PIKE TREND ANALYSIS USING THE LEAST-SQUARES MEANS APPROACH
================
mk
2019-05-22

------------------------------------------------------------------
==================================================================

### PIKE TRENDS Africa only for COP18 information document

(exclude NewMIKESite, line 80)
==============================

------------------------------------------------------------------
==================================================================

Section 1. LSMENAS

PIKE $PIKE\_{is} = \\frac{IC\_{is}}{IT\_{is}}$

*P**I**K**E*<sub>*i**s*</sub> ∼ *N**o**r**m**a**l*(*μ*<sub>*i**s*</sub>, *σ*<sup>2</sup>) *μ*<sub>*i**s*</sub> = *I**n**t**e**r**c**e**p**t* + *Y**e**a**r*<sub>*s*</sub> + *S**u**b**r**e**g**i**o**n*<sub>*i*</sub>

Section 2. Implementation in R
------------------------------

Load the requred libraries.

``` r
library(gplots) # for barplot2
```

    ## 
    ## Attaching package: 'gplots'

    ## The following object is masked from 'package:stats':
    ## 
    ##     lowess

``` r
library(doBy)   # for LSMEANS
library(dplyr)  # for data manipulation
```

    ## 
    ## Attaching package: 'dplyr'

    ## The following objects are masked from 'package:stats':
    ## 
    ##     filter, lag

    ## The following objects are masked from 'package:base':
    ## 
    ##     intersect, setdiff, setequal, union

``` r
library(knitr)
```

``` r
knitr::knit_exit()
```
