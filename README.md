Regression simulation function

[![Build Status](https://travis-ci.org/lebebr01/simglm.svg?branch=master)](https://travis-ci.org/lebebr01/simglm)
[![codecov.io](https://codecov.io/github/lebebr01/simglm/coverage.svg?branch=master)](https://codecov.io/github/lebebr01/simglm?branch=master)

A flexible suite of functions to simulate nested data.  
Currently supports the following features:
* Longitudinal data simulation
* Two levels of nesting
* Specification of distribution of random effects
* Specification of distribution of within cluster errors
* Specification of serial correlation
* Specification of population parameters
 *Including both fixed and random effects
* Specification of the number of variables
 * Ability to add time-varying covariates
 * Specify the mean and variance of fixed covariate variables
* Generation of mixture normal distributions
 * Ability to compute variance of each normal distribution in each mixture distribution
   based on equal weighting.
* Cross sectional data simulation
* Single level simulation

Features coming soon:
* Adding factor variable simulation
* More options for simulating random components
 * More distributions
 * Ability to simulate different distributions for different random effects
* Power by simulation
* Missing Data
* Ability to specify correlation amount random effects individually.
* Expand variance of mixture distribution function to include unequal weighting.

## Package Installation
This package can be installed by using the devtools package.


```r
library(devtools)
install_github("lebebr01/simReg")
library(simReg)
```

## Introduction to the simReg package
The best way to become oriented with the `simReg` package is through the package vignette.  There are two ways to get to the vignette (both will open a browser to view the vignette):


```r
browseVignettes()
vignette("Intro", package = "simReg")
```

Note: You may need to tell R to build the vignettes when installing the `simReg` package by doing the following:

```r
install_github("lebebr01/simReg", build_vignettes = TRUE)
```


Enjoy!
