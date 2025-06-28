# BEL-30-day-stock-price-forecasting

This project forecasts the **next 30 days of Bharat Electronics Ltd. (BEL)** stock prices using the **ARIMA time series model** in R.  
It uses historical data from Yahoo Finance and visualizes the forecast using `ggplot2`.

## 📥 Data Source

- **Ticker**: `BEL.NS`
- **Source**: Yahoo Finance (via `quantmod`).

- ## 🔮 Forecast Method

The project uses the **`auto.arima()`** function to automatically select the best ARIMA model for BEL’s historical closing prices.

**Forecast Horizon**: 30 Days  
**Outputs**:
- Predicted closing prices
- 95% Confidence Interval
- Visualization using `ggplot2`.

- ## 📉 Forecast Plot

- - **Red Line**: Predicted prices
- **Shaded Area**: 95% confidence interval.

- ## 📊 Interpretation

- The model suggests a **slight upward trend** in BEL's stock over the next 30 days.
- The confidence interval widens over time, indicating **growing uncertainty**.

- ## 📋 How to Run This Project

1. Open RStudio
2. Install packages:
   ```r
   install.packages(c("quantmod", "forecast", "ggplot2", "tidyverse")).

-- ## Author 
-- Anshu Kumar.
