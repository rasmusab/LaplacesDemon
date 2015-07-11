LaplacesDemon
=============

NB. This is a copy of the last commit of Statisticat/LaplacesDemon. At the time of writing, that repo is not available.  It is here for my own convenience.

A complete environment for Bayesian inference within R

The goal of `LaplacesDemon`, often referred to as LD, is to provide a complete and self-contained Bayesian environment within R. For example, this package includes dozens of MCMC algorithms, Laplace Approximation, iterative quadrature, Variational Bayes, parallelization, big data, PMC, over 100 examples in the Examples vignette, dozens of additional probability distributions, numerous MCMC diagnostics, Bayes factors, posterior predictive checks, a variety of plots, elicitation, parameter and variable importance, Bayesian forms of test statistics (such as Durbin-Watson, Jarque-Bera, etc.), validation, and numerous additional utility functions, such as functions for multimodality, matrices, or timing your model specification. Other vignettes include an introduction to Bayesian inference, as well as a tutorial.

There are many plans for the growth of this package, and many are long-term plans such as to cotinuously stockpile distributions, examples, samplers, and optimization algorithms. Contributions to this package are welcome.

The main function in this package is the `LaplacesDemon` function, and the best place to start is probably with the LaplacesDemon Tutorial vignette.

# Installation #
---

Using the 'devtools' package:

    install.packages("devtools")
    library(devtools)
    install_github("ecbrown/LaplacesDemon")

