Problem statement.

This project focuses on building a simple multiple linear model. The purpose of the analysis is explanation.


We review the dataset and some initial data analysis, model selection and validation, and detailed diagnostics.

We also explain why we do not transform the data, we check for problems with the predictors and provide our conclusions from the analysis.


Requirements.

#install packages

install.packages(c("StanHeaders","rstan"),type="source")

all.packages(c("coda","mvtnorm","devtools","dagitty"))

library(devtools)

devtools::install_github("rmcelreath/rethinking")

install.packages("faraway")

install.packages("dplyr")

install.packages("ggplot2")

install.packages("dagitty")

install.packages("Matching")

install.packages("rgenoud")


Dataset.

WaffleDivorce dataset used in this project can be gotten from the rethinking package in R.


References.

[1] Faraway, J. J. (2015). Linear Models with R. (2nd ed.). Boca Raton: Chapman & Hall/CRC.

[2] McElrealth, R. (2020). Statistical Rethinking: A Bayesian Course with Examples in R and Stan. (2nd ed.). Boca Raton: 
Chapman & Hall/CRC.

[3] Rencher, A. C. and G. B. Schaalje. (2008). Linear Models in Statistics. (2nd ed.). New York: Wiley.
