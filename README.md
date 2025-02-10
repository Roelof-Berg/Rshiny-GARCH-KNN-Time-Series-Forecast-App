# Time Series Forecasting
Time series forecasting is a quantitative meathod of analysing data over periods of time with the purpose of predict future trends and patterns.  This R App aims to make an easily manageable tool that can assist in risk management and investment decisions while providing adaptable, realistic and informative insights and analysis for major financial assets such as Stocks, Currencies, and Bonds by accounting for volatility dynamics, asymmetry, and variance. 



## Features:
- Machine Learning and Neural Network Price Forecasting using LSTM, ARIMA, and MSGARCH.
- Dynamic Conditional Correlation (DCC) Analysis with 2 Assets.
- Multivariate and Univariate Model Analysis with sGARCH, eGARCH, and gjrGARCH.
- Historical Risk Analysis with VaR and ES.
- Projected Risk Analysis with GARCH models.
- Annualized Sharpe, VaR, and Expected Shortfall (ES) Outputs at 95% confidence Interval.







## sGARCH, eGARCH, gjrGARCH, MSGARCH

### sGARCH

### eGARCH

### gjrGARCG

### MSGARCH




## K-NN 
K-NN (k-nearest neighbors) is a regression and classification model that predicts a target value by averaging the values of its nearest neighbours (data-points of an applied input). K-NN is a non-parametric and instance-based learning algorithm that can learn when a test-point is provided, making it effective for continuous and non linear data predictions. In this app K-NN is used to forecast returns based on lagged returns and volatility (supported by GARCH) and how RMSE changes with different k values.


# Installation
Several libraries must be installed which can all be done with a single line in `R`:

```bash
install.packages(c("shiny", "shinythemes", "quantmod", "rugarch", "FNN", "plotly", "caret", "zoo", "rmgarch", "PerformanceAnalytics"))
```

# Set Up and Running the App

The only prerequisites needed to set-up and run the App are to install the above packages. Any important additional Notes for customisation or error decoding will be written alongside the function code in the app.  


Working on: 
- Debugging Stock Price Forecast- Fatal Error from TORCH package
- DCC with 2+ Assests
  
