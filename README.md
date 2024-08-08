[📈 Click here to view the report on the browser](https://nadzmi27.github.io/Retail-Forecasting/)

# Background
The goal of this project is to forecast a time series of retail sales data using Exponential Smoothing ([ETS](https://otexts.com/fpp3/expsmooth.html)) and AutoRegressive Integrated Moving Average ([ARIMA](https://otexts.com/fpp3/arima.html)) models.
Using tools and techniques found in [Forecasting: Principles and Practice (3rd ed)](https://otexts.com/fpp3/)

# Key Forecasting Goals:
1. **Future Sales Predictions:** Generate forecasts for retail sales to understand future trends and patterns.
2. **Model Comparison**: Evaluate which forecasting method (ETS or ARIMA) provides more accurate predictions for the given time series.
3. **Performance Evaluation:** Compare your forecasts against actual data obtained from the ABS website to assess the accuracy of your models.

# Tools/Techniques Explored and Their Application:
1. [Seasonality Analysis](https://otexts.com/fpp3/seasonal-plots.html)
> **Retail Promotions:** Analyse seasonality to time promotions and sales events. For instance, identifying peak sales periods during holidays or special events allows retailers to plan discounts and inventory accordingly.
2. Trend Analysis with [ACF](https://otexts.com/fpp3/acf.html)
> **Sales Forecasting:** Use trend analysis to understand long-term sales patterns. For example, a retail chain might use ACF to identify upward or downward trends in sales over several years, helping in long-term planning and strategy.
3. [STL Decomposition](https://otexts.com/fpp3/stl.html)
> **Demand Planning:** Decomposing time series into trend, seasonal, and residual components helps businesses separate underlying trends from seasonal variations. A supermarket chain might use STL decomposition to forecast demand for seasonal products like holiday-themed goods.
4. Data Transformation using [Unit Root Test](https://otexts.com/fpp3/stationarity.html)
> **Model Preparation:** Before applying forecasting models, businesses transform data to ensure stationarity. For example, a fashion retailer might use differencing to stabilize variance in sales data before applying ARIMA models to forecast future sales.
5. Using [ACF and PACF to find MA and AR components](https://otexts.com/fpp3/seasonal-arima.html) (respectively) for the ARIMA  model.
> **ARIMA Model Specification:** Retailers use ACF and PACF to determine the order of ARIMA models for accurate forecasting.
6.  Using [Holt-Winter’s](https://otexts.com/fpp3/holt-winters.html) method which captures trend and seasonality for the ETS model
> **Seasonal Sales Forecasting:** Holt-Winter’s method is used for forecasting trends and seasonality. For example, a retailer with seasonal sales patterns (e.g., increased sales during summer) might use Holt-Winter’s method to forecast future seasonal demand.
7.  Using [AIC](https://otexts.com/fpp3/selecting-predictors.html) (by varying parameters) and [RMSE](https://otexts.com/fpp3/accuracy.html) to find the best ARIMA/ETS model.
> **Choosing the Best Model:** AIC helps in selecting the best model by balancing fit and complexity.
8. [Model Diagnostic](https://otexts.com/fpp3/diagnostics.html) such as _Residual Diagnostic_ and _Ljung-Box test_
> **Model Validation:** Diagnostics are used to check model adequacy. Retailers apply these tests to ensure that the residuals from their forecasting models are white noise, confirming that the model has captured the underlying data structure.
9. [Model Comparison](https://otexts.com/fpp3/arima-ets.html) between selected ARIMA and ETS using RMSE, MAE, MPE and MAPE
> **Choosing the Best Forecasting Method:** By comparing models using various metrics, retailers can select the best method for their needs.
10. [Out-Of-Sample Forecasting](https://otexts.com/fpp3/accuracy.html)
> **Strategic Planning:** Forecasting beyond the available data helps businesses plan for future growth. For example, a retailer might use out-of-sample forecasts to make strategic decisions about expanding stores or launching new products.
