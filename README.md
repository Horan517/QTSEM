
<!-- README.md is generated from README.Rmd. Please edit that file -->

# QTSEM

<!-- badges: start -->
<!-- badges: end -->

The goal of QTSEM is to present a Structural Equation Modeling (SEM)
example in R. It uses a travel behavior and collected during July to
August on Qinghai-Tibet Plateau as the example dataset.

## Installation

You can install the development version of QTSEM from GitHub with:

``` r
if(!require(remotes)){
    install.packages("remotes")
    library(remotes)
}
remotes::install_github("Horan517/QTSEM")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(QTSEM)
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```