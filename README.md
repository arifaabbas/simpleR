
# simpleR

<!-- badges: start -->
<!-- badges: end -->

The goal of simpleR is to provide a user with zero R experience to to import a dataset,view the dataframe and variables, detect missing data, get summary statistics, remove/keep variables, rename variables, change class of a variable, recode variable values and conduct an in-depth multiple regression with easy to understand summaries. This is all done in the console as the user selects different options in an interactive way. 

## Installation

You can install the released version of simpleR from github:
``` r

if(!require(remotes)){
  install.packages("remotes")
}
remotes::install_github("arifaabbas/simpleR")
```

## Example

This is what should be ran to initiate the simpleR interactive element in the console that will guide you through data management
and analysis:

``` r
library(simpleR)
simple()

```


