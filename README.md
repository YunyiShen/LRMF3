
<!-- README.md is generated from README.Rmd. Please edit that file -->

# LRMF3

<!-- badges: start -->

[![Codecov test
coverage](https://codecov.io/gh/RoheLab/LRMF3/branch/master/graph/badge.svg)](https://codecov.io/gh/RoheLab/LRMF3?branch=master)
[![R build
status](https://github.com/RoheLab/LRMF3/workflows/R-CMD-check/badge.svg)](https://github.com/RoheLab/LRMF3/actions)
<!-- badges: end -->

`LRMF3` is a developer facing package designed to provide a standardized
representation of low rank matrix factorization objects using the S3
object system.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("RoheLab/fastadi")
```

## Notes to self

*Conventions*

  - `mf` refers to SVD like matrix factorizations
  - `fa` refers to FA like matrix factorizations

*Related work*

  - <https://bradleyboehmke.github.io/HOML/GLRM.html>
  - <https://github.com/rexyai/rsparse/blob/master/R/MatrixFactorizationRecommender.R>
