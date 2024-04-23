# derivative_pricing

This repo consists of the task related to derivative pricing:

* <u>copulas</u> folder focused on choosing the best copula for the two time-series of BRENT/USD price and USD/RUB FX rate. Using right copula enables to simulate joint distribution and price composite options.

* <u>closest_PSD_matrix</u> file is devoted to finding closest positive definite matrix from the given one. Such task comes up often when we have negative-definite correlation matrix of financial assets  and we would like to generate new points for these correlated financial assets. Cholesky decomposition provides useful deconstruction of correlation matrix to lower diagonal matrices but it works only for positive semi-definite matrices.

* <u>Kalman_filter</u> file is dedicated to:

  a) generating simulations using "random walk plus noise" model

  b) calibrating Kalman filter parameters to distill true signals from observations with noise

  c) checking whether Kalman filter prediction is better than simple "last-observation" prediction

