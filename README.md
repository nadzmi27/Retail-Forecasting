[📈 Click here to view the report on the browser](https://nadzmi27.github.io/Retail-Forecasting/)

# Background
The goal of this project is to forecast a time series of retail sales data using Exponential Smoothing (ETS) and AutoRegressive Integrated Moving Average (ARIMA) models.
Using tools and techniques found in [Forecasting: Principles and Practice (3rd ed)](https://otexts.com/fpp3/)

# Key Forecasting Goals:
1. **Future Sales Predictions:** Generate forecasts for retail sales to understand future trends and patterns.
2. **Model Comparison**: Evaluate which forecasting method (ETS or ARIMA) provides more accurate predictions for the given time series.
3. **Performance Evaluation:** Compare your forecasts against actual data obtained from the ABS website to assess the accuracy of your models.

# Tools and Techniques Explored:
- [Seasonality Analysis](https://otexts.com/fpp3/seasonal-plots.html)
- Trend Analysis with ACF
- [STL Decomposition](https://otexts.com/fpp3/stl.html)
- Data Transformation using [Unit Root Test](https://otexts.com/fpp3/stationarity.html)
- Using [ACF and PACF to find MA and AR components](https://otexts.com/fpp3/seasonal-arima.html) (respectively) for the ARIMA  model
- Using [AIC](https://otexts.com/fpp3/selecting-predictors.html) (by varying ARIMA parameters) to find the best ARIMA model
- Using RMSE to measure prediction error of forecasted value
- Using [Holt-Winter’s](https://otexts.com/fpp3/holt-winters.html) method which captures trend and seasonality for the ETS model
- Using AIC and RMSE on the ETS model for the same purpose as the ARIMA model
- [Model Diagnostic](https://otexts.com/fpp3/diagnostics.html) such as _Residual Diagnostic_ and _Ljung-Box test_
- Model Comparison between selected ARIMA and ETS using RMSE, MAE, MPE and MAPE
- [Out-Of-Sample Forecasting](https://otexts.com/fpp3/accuracy.html)
