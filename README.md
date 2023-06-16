
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to make splitting one string easier.  
\> This is a toy package for learning purposes

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("CarolinaPB/regexcite")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)
str_split_one("a,b,c", pattern = ",")
#> [1] "a" "b" "c"
```
