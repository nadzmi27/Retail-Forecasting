# Background
The goal of this project is to forecast a time series of retail sales data using Exponential Smoothing (ETS) and AutoRegressive Integrated Moving Average (ARIMA) models.
Using tools and techniques found in [Forecasting: Principles and Practice (3rd ed)](https://otexts.com/fpp3/)

# Key Forecasting Goals:
1. **Future Sales Predictions:** Generate forecasts for retail sales to understand future trends and patterns.
2. **Model Comparison**: Evaluate which forecasting method (ETS or ARIMA) provides more accurate predictions for the given time series.
3. **Performance Evaluation:** Compare your forecasts against actual data obtained from the ABS website to assess the accuracy of your models.

# Tools and Techniques Explored:
- Seasonality Analysis
- Trend Analysis with ACF
- STL Decomposition
- Data Transformation using Unit Root Test
- Using ACF and PACF to find MA and AR components (respectively) for ARIMA  model
- Using AIC (by varying ARIMA parameters) to find the best ARIMA model
- Using RMSE to measure prediction error of forecasted value
- Using Holt-Winter’s method which capture trend and seasonality for ETS model
- Using AIC and RMSE on ETS model for the same purpose as ARIMA model
- Model Dianostic such as Residual Diagnostic and Ljung-Box test
- Model Comparison between selected ARIMA and ETS using RMSE, MAE, MPE and MAPE
- Out-Of-Sample Forecasting
