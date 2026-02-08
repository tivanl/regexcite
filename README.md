
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->

<!-- badges: end -->

The goal of regexcite is to assist in working with strings in R.

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("tivanl/regexcite")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)
## basic example code
str_split_one("a,b,c", ",")
#> [1] "a" "b" "c"
str_split_one("a,b,c", ",", n = 2)
#> [1] "a"   "b,c"
```

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
