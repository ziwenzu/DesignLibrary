DesignLibrary: A Library of Common Research Designs
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis-CI Build
Status](https://travis-ci.org/DeclareDesign/DesignLibrary.svg?branch=master)](https://travis-ci.org/DeclareDesign/DesignLibrary)
[![Coverage
Status](https://coveralls.io/repos/github/DeclareDesign/DesignLibrary/badge.svg?branch=master)](https://coveralls.io/github/DeclareDesign/DesignLibrary?branch=master)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/DesignLibrary)](https://cran.r-project.org/package=DesignLibrary)
[![minimal R
version](https://img.shields.io/badge/R%3E%3D-3.4.0-6666ff.svg)](https://cran.r-project.org/)
[![packageversion](https://img.shields.io/badge/Package%20version-0.1.4.9999-orange.svg?style=flat-square)](commits/master)

**DesignLibrary** provides simple interface to build designs using the
package **DeclareDesign**. In one line of code users can specify the
parameters of individual designs and diagnose their properties. The
designers can also be used to compare performance of a given design
across a range of combinations of parameters, such as effect size,
sample size, assignment probabilities and more.

[Check out the online version of the library
here](https://declaredesign.org/library/).

-----

## Installing the design library

To install the latest stable release of **DesignLibrary**, please ensure
that you are running version 3.4 or later of R and run the following
code:

``` r
install.packages("DesignLibrary")
```

If you would like to use the latest development release of
**DesignLibrary**, please ensure that you are running version 3.4 or
later of R and run the following
code:

``` r
devtools::install_github("DeclareDesign/DesignLibrary", keep_source = TRUE)
```

## Contributing designs and designers

We welcome contributions to the library\!

  - You can [submit static
    designs](https://declaredesign.org/library/articles/how_to_write_and_contribute_designs.html)
    made in `DeclareDesign`, which will live as properly attributed
    entries in the library on our website
  - Or you can [submit designer functions that generate
    designs](https://declaredesign.org/library/articles/how_to_write_and_contribute_designers.html),
    which may be added to the CRAN version of the package

-----

This project is generously supported by a grant from the [Laura and John
Arnold Foundation](http://www.arnoldfoundation.org) and seed funding
from [Evidence in Governance and Politics (EGAP)](http://egap.org).
