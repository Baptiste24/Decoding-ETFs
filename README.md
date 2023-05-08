# Decoding-ETFs
This project focuses on classification problem of 101 unidentified ETFs and decoding a mystery allocation made up of our 101 ETFs

We first compute the coefficient of variation and sharpe ratio for each ETFs and macro factors.

In order to identify and flag each ETFs we use clustering algorithm K-means and gaussian mixture, we do this on our ETFs and Macro factors like the S&P500. We then obtain clusters for the coefficient of variation and Sharpe ratio. By doing so we can have a matching between our macro factors and the ETFs.

later we use a LASSO regression to obtain the weights of each of our ETFs in the mystery allocation based on the ETFs time series and the mystery allocation time series.

Please refer to the attached jupyter notebook for further details

Lastly we failed to implement the Kalman filter to do the same exercice but with a mystery allocation varying each day. The code is yet let in the notebook.
