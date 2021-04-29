# A Yen for the Future

## Summary

The following code attempts to predict the future movements of Yen to US Dollar through time-series and linear regression analysis. Below are a summary of the data and findings.

### ARMA Model
The ARMA model has forecasted the Yen Futures to have positive returns over the next 5 days. Based on the high P values, we should review the model to find a better fit.  
![](/Resources/arma_plot.png)
### ARIMA Model
The ARIMA model has forecasted the Yen Futures settle prices to increase over the next 5 days. Based on the high P values, we should review the model to find a better fit.  
![](/Resources/arima_plot.png)
### GARCH Model
The GARCH model has forecasted the volatility of Yen Futures returns to increase over the next 5 days. Based on the P value of 1 day lags returning a value below 0.05, the model is a good fit. This also suggests that volatility is easier to predict than returns and price.  
![](/Resources/garch_plot.png)
### Linear Regression Model
The model has performed better with Out-of-Sample data, which had a Root Mean Square Error of 0.4154, than In-Sample data, which had a Root Mean Square Error of 0.5963. This suggests that the model performs well, as it has outperformed even with data the model has not seen before.  
![](/Resources/reg_plot.png)