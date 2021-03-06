
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `dearseq`

<!-- [![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/dearseq)](https://cran.r-project.org/package=dearseq) -->

[![Travis-CI Build
Status](https://travis-ci.org/borishejblum/dearseq.svg?branch=master)](https://travis-ci.org/borishejblum/dearseq)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/borishejblum/dearseq?branch=master&svg=true)](https://ci.appveyor.com/project/borishejblum/dearseq)
[![Coverage
Status](https://img.shields.io/codecov/c/github/borishejblum/dearseq/master.svg)](https://codecov.io/github/borishejblum/dearseq?branch=master)
<!-- [![Downloads](https://cranlogs.r-pkg.org/badges/dearseq?color=blue)](https://www.r-pkg.org/pkg/dearseq) -->

## Overview

`dearseq` is a package for analyzing RNA-seq data. The 2 main functions
of the package are `dear_seq()` and `dgsa_seq()`:

  - **Gene-wise Differential Analysis of RNA-seq data** can be performed
    using the function `dear_seq()`.
  - **Gene Set Analysis of RNA-seq data** can be performed using the
    function `dgsa_seq()`.

The methods implemented in this package are detailed in the following
articles:

> Gauthier M, Agniel D, Thiébaut R & Hejblum BP (2019). dearseq: a
> variance component score test for RNA-Seq differential analysis that
> effectively controls the false discovery rate, *bioRxiv* 635714.
> [DOI: 10.1101/635714](https://doi.org/10.1101/635714)

> Agniel D & Hejblum BP (2017). Variance component score test for
> time-course gene set analysis of longitudinal RNA-seq data,
> [*Biostatistics*](https://academic.oup.com/biostatistics/article-abstract/18/4/589/3065599),
> 18(4):589-604. [arXiv:1605.02351](https://arxiv.org/abs/1605.02351v4)
> [DOI: 10.1093/biostatistics/kxx005](https://doi.org/10.1093/biostatistics/kxx005)

## Installation

***`dearseq` is currently [under
review](https://github.com/Bioconductor/Contributions/issues/1307) to be
included in [Bioconductor](http://www.bioconductor.org)***

Meanwhile, the easiest way to get `dearseq` is to install its
development version from the `dev` branch on
[GitHub](https://github.com/borishejblum/dearseq):

``` r
#install.packages("devtools")
devtools::install_github("borishejblum/dearseq", ref="dev")
```

– Marine Gauthier, Denis Agniel & Boris Hejblum
