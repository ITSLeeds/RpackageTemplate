
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis build
status](https://travis-ci.org/ITSLeeds/RpackageTemplate.svg?branch=master)](https://travis-ci.org/ITSLeeds/RpackageTemplate)
[![Coverage
status](https://codecov.io/gh/ITSLeeds/RpackageTemplate/branch/master/graph/badge.svg)](https://codecov.io/github/ITSLeeds/RpackageTemplate?branch=master)
[![Build
status](https://ci.appveyor.com/api/projects/status/gqp3smc04as3qg85?svg=true)](https://ci.appveyor.com/project/layik/RpackageTemplate-05ana)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

# RpackageTemplate

Template to form the basis of ITSLeeds R packages

## Installation

Install the package with **remotes** as
follows:

``` r
install.packages("remotes") # If you do not already have the remotes package
remotes::install_github("ITSleeds/RpackageTemplate")
```

## Usage

To create a new package and get it on your computer:

  - Create a new repo on GitHub in an appropriate organisation. You can
    use this template by clicking the “[Use this
    template](https://github.com/ITSLeeds/RpackageTemplate/generate)”
    button in the top right hand corner of this page.
  - Clone the package onto your computer, e.g. by typing `git clone
    git@github.com:itsleeds/youPackageName` in a Linux terminal (try
    pressing `Ctl+Shift+T` in RStudio to get to the terminal or open
    Windows Powershell)
  - Change the name of the .Rproj file, e.g. with the following commands
    in terminal

<!-- end list -->

``` bash
cd testPackage
mv RpackageTemplate.Rproj yourPackageName.Rproj
```

  - Open the project in RStudio as follows:

<!-- end list -->

``` r
rstudioapi::openProject("/path/to/yourPackageName")
```

## Continuous integration

To add continuous integration, use the following commands:

``` r
# usethis::use_pkgdown()
usethis::use_pkgdown_travis()
travis::use_travis_deploy()
```

See these resources for further information:

  - <https://pkgdown.r-lib.org/articles/pkgdown.html>
  - <https://pkgdown.r-lib.org/reference/deploy_site_github.html>

## Acknowledgement

Acknowledge all the fine people who helped build this package.

## Contribution

Please note that the `RpackageTemplate` project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By contributing to
this project, you agree to abide by its terms.

## Package Status

This package is part of ongoing research at the University of Leeds, it
is provided “as is” and is likely to be updated and changed without
warning to meet the research needs of the University.
