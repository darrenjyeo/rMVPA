
Multivoxel Pattern Analysis in R
--------------------------------

[![codecov](https://codecov.io/gh/rMVPA/NA/branch/master/graph/badge.svg)](https://codecov.io/github/bbuchsbaum/rMVPA?branch=master) [![Build Status](https://travis-ci.org/rMVPA/NA.svg?branch=master)](https://travis-ci.org/bbuchsbaum/rMVPA)

### This package is under development.

### Introduction

`rMVPA` is an R library for multivariate pattern analysis of neuroimaging data. The goal of this library is to make MVPA analyses easy. It can be used both programmatically from within R or using a command line interface. 'rMVPA' leverages the 'caret' library for the underlying machine learning interface. What `rMVPA` provides is the infrastructure for conducting machine learning analyses on neuroimaging data.

Documentation and vignettes: <https://bbuchsbaum.github.io/rMVPA/>

### Installation

### Using devtools

To install `rMVPA` from within R, use the `devtools` function `install_github`. You will need the development version of `neuroim2` as well.

From within R:

    library(devtools)
    install_github("bbuchsbaum/neuroim2")
    install_github("bbuchsbaum/rMVPA")

### Using `git` from the command line

    git clone git@github.com:bbuchsbaum/rMVPA.git
    R CMD install rMVPA

### Optionally install command line scripts for "coding-free" MVPA analysis:

`wget https://raw.githubusercontent.com/bbuchsbaum/rMVPA/master/scripts/MVPA_Searchlight.R`

`wget https://raw.githubusercontent.com/bbuchsbaum/rMVPA/master/scripts/MVPA_Regional.R`

Then, move these files to a folder on your `PATH` and make them executable:

`chmod +x MVPA_Searchlight.R`

`chmod +x MVPA_Regional.R`
