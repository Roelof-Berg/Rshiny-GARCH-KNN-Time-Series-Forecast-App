# Time Series Forecasting
Time series forecasting is a quantitative meathod of analysing data over periods of time with the purpose of predict future trends and patterns.  This R App aims to make an easily manageable tool that can assist in risk management while providing adaptable, realistic and informative insights and analysis for major financial assets such as Stocks, Currencies, and Bonds by accounting for volatility dynamics, asymmetry, and variance. 



## Features:
- Price Forecasting
- Volatility Dynamics Analysis and Forecasting for Portfolio Risk Management
- Annualized Sharpe, VaR, and Expected Shortfall
- Multivariate and Univariate Model Analysis with sGARCH, eGARCH, and gjrGARCH
- Dynamic Conditional Correlation (DCC) Analysis with 2 Assets




## sGARCH, eGARCH, gjrGARCH
---


## K-NN 
K-NN (k-nearest neighbors) is a regression and classification model that predicts a target value by averaging the values of its nearest neighbours (data-points of an applied input). K-NN is a non-parametric and instance-based learning algorithm that can learn when a test-point is provided (through quantmod api), making it effective for continuous and non linear data predictions. In this app K-NN is used to forecast returns based on lagged returns and volatility (supported by GARCH) and how RMSE changes with different k values.


# Installation
Several libraries must be installed which can all be done with a single line in `R`:

```bash
install.packages(c("shiny", "shinythemes", "quantmod", "rugarch", "FNN", "plotly", "caret", "zoo", "rmgarch", "PerformanceAnalytics"))
```

# Set Up and Running the App

After the libraries are installed into an R IDE such as RStudio you should then set up a Rshiny web app file/folder then you can copy/paste the server logic into the server console and UI into UI console then run app.

NOTE: For now, to use the Historical risk section of the app, set the rolling window to 60 days or below. The goal is to improve this to 247 days in the future.


Working on: 
- Debugging Historical risk Model
  - `Failed to invert Hessian` - rugarch warning
  - `warning in sqrt(): NaNs produced`
  - `Warning in .gjrgarchfit(spec = spec, data = data, out.sample = out.sample,` 
- DCC with 2+ Assests
