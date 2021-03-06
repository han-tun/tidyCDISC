
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0) 

<img src="inst/app/www/Biogen.png" align="right" height="15%" width="15%"/>

# tidyCDISC 

<img src="man/figures/hex-tidyCDISC.png" align="right" height="15%" width="15%"/>

The purpose of tidyCDISC is a shiny app to easily create custom tables
and figures from ADaM datasets.

[Read our help page here](https://tidycdisc.netlify.app/)

# Installation

``` r
remotes::install_github("Biogen-Inc/tidyCDISC")
```

# Use Case

Using the dev/run\_dev.R file, you can run the application locally:

``` r
# Set options here
options(golem.app.prod = FALSE) # TRUE = production mode, FALSE = development mode

# Detach all loaded packages and clean your environment
golem::detach_all_attached()

# Document and reload your package, which runs these three functions...
golem::document_and_reload()

# Run the application 
run_app()
```

