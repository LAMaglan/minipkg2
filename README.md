
<!-- README.md is generated from README.Rmd. Please edit that file -->

# minipkg2

<!-- badges: start -->

[![R-CMD-check](https://github.com/LAMaglan/minipkg2/workflows/R-CMD-check/badge.svg)](https://github.com/LAMaglan/minipkg2/actions)
<!-- badges: end -->

Note: this was a follow-along tutorial: <br>
<https://masalmon.eu/talks/2021-03-26-package-dev/> <br> The goal of
minipkg2 is to tell you what the time is.

## Installation

``` r
# install.packages("remotes")
remotes::install_github("LAMaglan/minipkg2")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(minipkg2)
what_time()
#> [1] "Aye! Il est maintenant 14:27!"
```
