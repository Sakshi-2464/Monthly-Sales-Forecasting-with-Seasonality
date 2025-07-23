# Monthly Sales Forecasting with Seasonality
This project demonstrates a basic time series forecasting workflow using simulated monthly sales data over two years. It includes visualization, decomposition, and forecasting using both **Seasonal Naive** and **Holt-Winters Exponential Smoothing** methods.

## Tools Used
- Python
- pandas, numpy
- matplotlib
- statsmodels

## Project Highlights
- **Simulated Data Creation**: Sales trend + seasonal spikes (e.g., holiday peaks in December)
- **Data Visualization**: Clear line plots of historical sales
- **Decomposition**: Trend, seasonality, and noise using `seasonal_decompose`
- **Forecasting**:
  - **Seasonal Naive**: Copies values from the same month in the previous year
  - **Holt-Winters Method**: Captures both trend and seasonality for better forecasts
- **6-Month Forecast**: Visual comparison between naive and advanced methods
