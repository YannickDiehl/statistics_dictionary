# How to simulate data in R

## Setup

    library(faux)

## Simulation Population

Simulation einer Population.

    data <- rnorm_multi(
      n = 200, 
      mu = c(0, 45, 180),
      sd = c(3, 5, 5),
      r = c(0.5, 0.5, 0.25), 
      varnames = c("health", "age", "heigth"),
      empirical = FALSE
      )
