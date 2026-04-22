# Financial Forecasting: ARIMA & NGARCH Volatility Modeling
### Tools: Python, Pandas, Statsmodels | Data: Facebook (Meta) Stock Prices (2012–2021)

## Project Overview
This project analyzes 9 years of Facebook (Meta) stock history to forecast future price movements and model market volatility. By combining **ARIMA** (AutoRegressive Integrated Moving Average) and **NGARCH** (Nonlinear GARCH), the study provides insights into both the direction and the risk-profile of financial assets.

## Key Analytical Components

### 1. Price Forecasting with ARIMA
Selected for its ability to handle non-stationary financial data through differencing:
* **Preprocessing**: Converted date-time indexing and performed stationarity checks.
* **Model Implementation**: Utilized the `Statsmodels` library to fit the ARIMA architecture.
* **Objective**: Precisely predict price fluctuations while accounting for seasonal components.

### 2. Volatility Modeling with NGARCH
Implemented to address the nonlinearities and "volatility clustering" common in stock markets:
* **Asymmetry Handling**: Captures the "leverage effect" where stock price drops often lead to higher volatility than price increases.
* **Risk Assessment**: Provides a mathematical framework for analyzing the variance in daily returns.

## Methodology
- **Data Loading**: Processing 9 financial attributes (Open, High, Low, Close, Volume, etc.).
- **Differencing**: Stabilizing the mean of the time series to ensure model reliability.
- **Evaluation**: Validating forecasts against historical trading days.

