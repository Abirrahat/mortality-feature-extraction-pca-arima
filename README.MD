# Mortality Feature Extraction & Insurance Pricing

## Overview
This project analyzes long-term mortality trends in Bangladesh using crude death rate data from the World Bank. PCA is used to extract a latent mortality feature, which is then forecasted using ARIMA and applied to life insurance pricing.

## Methodology
- Log transformation and mean centering
- Outlier detection and capping (1971 mortality shock)
- Principal Component Analysis (PCA)
- ARIMA (1,1,0) time series forecasting
- Actuarial premium calculation with risk margins

## Key Results
- PCA captured the dominant long-term mortality trend
- ARIMA forecasts suggest continued mortality improvement
- Forecast uncertainty incorporated into insurance pricing

## Technologies
Python, pandas, sklearn, statsmodels, matplotlib

## Data Source
World Development Indicators – World Bank: https://data.worldbank.org/indicator/SP.DYN.CDRT.IN?locations=BD

## Links
- Medium article: https://medium.com/@abir6864/extracting-mortality-trends-using-pca-and-arima-an-actuarial-case-study-of-bangladesh-847ee0643023?sk=0055aa29cac8ceeb03e45b35d17fdcca
