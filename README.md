# Engle-Granger Cointegration Test

## Description
This test assesses cointegration between asset pairs, meaning a long-term statistical correlation and equilibrium. If asset prices diverge in the short term, that creates an arbitrage opportunity: short the overpriced asset and buy the underpriced asset until prices revert to the mean. This test pairs assets in the same industry, runs statistical tests on three years of historical price data, and uploads the completed test to a designated desktop folder. Asset pairs with an alpha less than 5% are statistically cointegrated and can be arbitraged if they are short-term mispriced.

## Getting Started
To run this test, you can run the cointegration Python script after installing the necessary pip packages. I hardcoded all NASDAQ tickers for simplicity. 

## Results
The results of this test are as of 05/23/2025. The file named "01-cointegration_results_2025-05-23" contains 37 asset pairs.
