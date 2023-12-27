# Jamaican Stock Investment Strategy

## Overview
This repository outlines a comprehensive investment strategy for deploying J$50 million JMD across five stocks listed on the Jamaica Stock Exchange. The strategy incorporates Short-Term Investments utilizing ARIMA models, sentiment analysis, and various forms of technical and fundamental analysis. Each stock's ARIMA model, along with additional insights, is detailed below.

## Grace Kennedy Stock - (GK) 
The ARIMA model for Grace Kennedy Stock (GK) involves:
- Data loading and stationarity checks using the Augmented Dickey Fuller (ADF) Test.
- Applying differencing once to achieve stationarity.
- Conducted Model parameter determination based on ACF and PACF plots.
- Conducted Model evaluation using AIC, BIC, and MSE.
- Selection of the BIC model of order (1,1,1) for forecasting.
- Did a Performance metrics assessment, revealing concerns about the F1 Score.
- Additional technical and fundamental analysis insights, including a recent trading volume spike on November 22, 2023 that might have happened due to investors taking advantage of dividend capture.
- Investment decision: Invest $10,000,000 JMD in GK due to expected low trading activity after the dividend payment date. 

## Caribbean Cement Company - (CCC) 
The ARIMA model for Caribbean Cement Stock (CCC) involves:
- Data loading and stationarity checks using the ADF Test.
- Determining model parameters based on ACF and PACF plots.
- Choosing the ARIMA(1,0,0) model after evaluating different models based on AIC, BIC, and MSE.
- Performance metrics assessment, predicting a Tuesday EOD closing price of $51.00.
- Additional insights from candlestick patterns indicating selling pressure.
- Investment decision: Invest $7,000,000 JMD in CCC due to predicted market movement.

## 138 Student Living Jamaica - 138SL
The ARIMA model for 138 Student Living Jamaica involves:
- Data loading and stationarity checks using the ADF Test.
- Applying differencing and selecting the BIC model of order (1,1,1) for forecasting.
- Performance metrics assessment, predicting a Tuesday EOD closing price of $4.16.
- Observed a bearish trend in the stock market, consistent with ARIMA forecasts.
- Investment decision: Invest $6,000,000 JMD in 138SL due to expected bearish trend continuation.

## Jamaica Public Service - JPS7
The ARIMA model for Jamaica Public Service (JPS7) involves:
- Data loading and stationarity checks using the ADF Test.
- Determining model parameters based on ACF and PACF plots.
- Choosing the ARIMA(1,0,1) model.
- Performance metrics assessment, predicting market movement.
- Observed a bullish trend in the stock market, consistent with ARIMA forecasts.
- Investment decision: Invest $25,000,000 JMD in JPS7 due to expected bullish trend. 

## Jamaica Broilers Group - JBG
The ARIMA model for Jamaica Public Service (JPS7) involves:
- Data loading and stationarity checks using the ADF Test.
- Determining model parameters based on ACF and PACF plots.
- Choosing the ARIMA (0,1,0) model.
- Performance metrics assessment, predicting market movement.
- Observed a bearish trend in the stock market, consistent with ARIMA forecasts.
- Investment decision: Invest $2,000,000 JMD in JBG due to expected bearish trend. 


## How to Use
1. Clone the repository: `git clone https://github.com/aurill/Jamaican_Stock_Investment_Strategy.git`
2. Explore the detailed insights and investment decisions for each stock in the respective sections.
3. Apply the investment strategy based on the provided analyses and forecasts.

## Dependencies
- Python 3.12
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn, itertools, tabulate

## Acknowledgments
- Data sourced from the Jamaica Stock Exchange.

