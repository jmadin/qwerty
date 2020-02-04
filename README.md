
fishflux: A tool to model nutrient fluxes in fish
=================================================

[![Build Status](https://api.travis-ci.org/nschiett/fishflux.png?branch=master)](https://travis-ci.org/nschiett/fishflux)

<img src="man/figures/fishflux.png" width = 120 alt="fishflux logo"/>

Overview
--------

The `fishflux` package provides a tool to model fluxes of C (carbon), N (nitrogen) and P (phosphorus) in fishes. It combines basic principles from elemental stoichiometry and metabolic theory. The package offers a user-friendly interface to apply the model. `fishflux` is ideal for fish ecologists wishing to predict ingestion, egestion and excretion to study fluxes of nutrients and energy. 

Main assets:
  
- Provides function to model fluxes of Carbon, Nitrogen and Phosphorus for fishes
- Allows for the estimation of uncertainty, dpending on the uncertainy of the input parameters
- Provides some functions to help find parameters as inputs for the model
- Provides functions to extract and illustrate results



Theoretical framework
---------------------

For more information on the theoretical framework behind `cnp_model`,
check out the paper (add link to paper).

Installing and loading fishflux
-------------------------------

`fishflux` uses Markov Chain Monte Carlo simulations provided by
[stan](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started).
Therefore, the first step is to install
[rstan](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started). It's important to closely follow all the steps described on the page depending on your operating system. 

### GitHub

The best way to install the latest development version of `fishflux` is
to install it from GitHub.

``` r
install.packages("devtools")
devtools::install_github("nschiett/fishflux", dependencies=TRUE)
library(fishflux)
```

### CRAN

`fishflux` will be available on CRAN in the future:

``` r
install.packages("fishflux")
library(fishflux)
```

### Downloaded package file

Another option is to download the source file available on github
[here](https://github.com/nschiett/fishflux).

``` r
install.packages(path_to_fishflux_file, repos = NULL, type="source")
library(fishflux)
```

Documentation
-------------

See package vignettes.

Citation
--------

Future releases
---------------
