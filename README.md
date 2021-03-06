# effsize
R effsize package for efficient effect size computation.

This package contains the functions to compute the standardized 
effect sizes for experiments 
(Cohen d, Hedges g, Cliff delta, Vargha and Delaney A). 

The computation algorithms have been optimized to allow efficient 
computation even with very large data sets.

The package is available on the CRAN web site: 
http://cran.r-project.org/web/packages/effsize/index.html

In case you wish using a version not yet on the CRAN web site you can use the `devtools` package:

```r
install.packages("devtools")  ## if not already installed
devtools::install_github("mtorchiano/effsize")
```

If you find the package useful and use it in your research, please consider citing it using the version published on Zenodo:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.196082.svg)](https://doi.org/10.5281/zenodo.196082)


### Dev Status

[![Build Status](https://travis-ci.org/mtorchiano/effsize.svg?branch=master)](https://travis-ci.org/mtorchiano/effsize)
[![CRAN Release](http://www.r-pkg.org/badges/version-last-release/effsize)](http://cran.r-project.org/web/packages/effsize)
[![Downloads](http://cranlogs.r-pkg.org/badges/last-month/effsize)](https://cranlogs.r-pkg.org)
