# Project Objective: 

Task: Use Stock Diversification Principles to decide how J$50 million JMD will be spent across five (5) stocks namely: Grace Kennedy (GK), Caribbean Cement Company Limited (CCC), 138 Student Living Jamaica Limited (138SL), Jamaica Broilers Group (JBG), & Jamaica Public Service (JPS7). 

# Grace Kennedy Stock (GK) ARIMA Forecast

## Overview
This repository implements an ARIMA (AutoRegressive Integrated Moving Average) forecast model for predicting the Tuesday End-of-Day (EOD) Closing price of Grace Kennedy Stock (GK). The model involves data loading, stationarity checks using the Augmented Dickey Fuller (ADF) Test, and parameter tuning based on ACF and PACF plots. The selected ARIMA model of order (1, 1, 1) is used for forecasting.

## Grace Kennedy Stock Insights
The ARIMA model for GK Stock provides insights into the stock's behavior and future predictions. Key observations and decisions include:

1. **Stationarity Check:**
   - The data was made stationary using differencing based on the Augmented Dickey Fuller (ADF) Test.

2. **Model Evaluation:**
   - Different ARIMA models were evaluated based on AIC, BIC, and MSE.
   - The BIC model of order (1, 1, 1) was chosen for forecasting.

3. **Forecasting Results:**
   - The model forecasted a Tuesday EOD Closing price under BIC, estimating it at $75.49.

4. **Performance Metrics:**
   - Metrics such as MAE, MSE, RMSE, and F1 score were used to assess model quality.
   - No signs of underfitting or overfitting were observed in regression metrics.

5. **Concerns and Further Analysis:**
   - The F1 Score raised concerns, indicating the need for further research.
   - The model forecasted the same closing price as the Friday EOD Stock Price, suggesting potential underfitting.

6. **Additional Analysis:**
   - Technical and fundamental analysis were employed for a more comprehensive insight.
   - A recent trading volume spike on November 22, 2023, was linked to an upcoming Interim Payment dividend on December 15, 2023.

7. **Investment Decision:**
   - Due to potential low trading activity after the Interim Payment dividend, a $10,000,000 JMD investment in GK is recommended for this week.
   - The report recognizes the long-standing quality of GK as a Blue-Chip Stock, justifying a significant investment.


## How to Use
1. Clone the repository: `git clone https://github.com/aurill/GK_Stock_ARIMA_Forecast.git`
2. Open and run the Jupyter notebook [GK_Stock_Forecast.ipynb] to explore the ARIMA model implementation.
3. Review the findings, insights, and investment recommendations in the notebook.

## Dependencies
- Python 3.12
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn, itertools, tabulate

## Acknowledgments
- The dataset used in this project is sourced from [GK_Quaterly_Stock_Prices.xlsx].

