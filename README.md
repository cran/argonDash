
<!-- README.md is generated from README.Rmd. Please edit that file -->

# argonDash <img src="http://www.rinterface.com/inst/images/argonDash.svg" width=200 align="right" />

[![R build
status](https://github.com/RinteRface/argonDash/workflows/R-CMD-check/badge.svg)](https://github.com/RinteRface/argonDash/actions)
[![CRAN
status](https://www.r-pkg.org/badges/version/argonDash)](https://cran.r-project.org/package=argonDash)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-ff69b4.svg)](https://lifecycle.r-lib.org/articles/stages.html#maturing)
[![cranlogs](https://cranlogs.r-pkg.org/badges/argonDash)](https://cran.r-project.org/package=argonDash)

> argon Bootstrap4 dashboard template for Shiny

## Installation

`{argonDash}` requires to install `{argonR}`.

``` r
install.packages("argonR")
# devel version
devtools::install_github("RinteRface/argonDash")
# from CRAN
install.packages("argonDash")
```

## Demo

``` r
library(argonDash)
argonDashGallery()
```

We provide some placeholder images served in the `images` folder, so you
just have to do this to access them:

``` r
argonAvatar(
  size = "sm",
  src = "images/undraw_profile-pic_fatv.svg"
)
```

### Vertical layout

<br> <img src="man/figures/argonDashDemo.png">

### Horizontal layout

This layout is experimental.

<br> <img src="man/figures/argonDashDemo_horizontal.png">

## Aknowledgement

- [Creative Tim](https://www.creative-tim.com/) for designing the
  original argon dashboard HTML template.

## Code of Conduct

Please note that the argonDash project is released with a [Contributor
Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
