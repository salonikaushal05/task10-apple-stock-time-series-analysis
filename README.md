# task10-apple-stock-time-series-analysis
# Task 10: Time Series Data Analysis on Apple Stock Data

##  Author
**Saloni Kaushal**

##  Objective
The objective of this project is to perform Time Series Analysis (TSA) on Apple Stock Market data and understand historical trends, seasonality, and future forecasting using Python.

##  Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
##  Dataset

**Dataset:** Apple Stock Market Data

The dataset contains historical stock prices of Apple Inc. including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Volume

For analysis, the **Date** and **Closing Price** columns were used.

##  Project Workflow

### 1. Data Loading
- Imported dataset using Pandas.
- Inspected dataset structure and columns.

### 2. Data Exploration
- Checked dataset dimensions.
- Verified data types.
- Identified missing values.

### 3. Data Preprocessing
- Converted the Date column into datetime format.
- Set Date as the index for time series analysis.

### 4. Time Series Visualization
- Visualized Apple stock closing prices over time.
- Observed trends and fluctuations in stock prices.

### 5. Stationarity Check
- Performed the Augmented Dickey-Fuller (ADF) Test.
- Evaluated whether the time series data was stationary.

### 6. Moving Average Analysis
- Calculated:
  - 7-Day Moving Average
  - 30-Day Moving Average
- Compared moving averages with actual stock prices.

### 7. Seasonal Decomposition
- Identified:
  - Trend Component
  - Seasonal Component
  - Residual Component

### 8. Forecasting
- Built an Exponential Smoothing model.
- Forecasted future stock prices for the next 30 days.

##  Key Visualizations

- Stock Closing Price Trend
- Moving Average Analysis
- Seasonal Decomposition Plot
- Forecasting Plot

## 📈 Results

- Successfully analyzed Apple stock market trends.
- Performed stationarity testing using the ADF Test.
- Identified trend and seasonal patterns.
- Generated forecasts for future stock prices.
- Visualized historical and forecasted data effectively.

##  Conclusion

Time Series Analysis helps in understanding historical data patterns and predicting future values. In this project, Apple stock market data was analyzed using statistical techniques and forecasting methods to gain insights into market behavior and future trends.

##  Learning Outcomes

- Understanding Time Series Data
- Data Preprocessing for Time Series Analysis
- Stationarity Testing using ADF Test
- Moving Average Analysis
- Seasonal Decomposition
- Forecasting using Exponential Smoothing
- Data Visualization Techniques

##  Internship Task

**Edutech Solution – Data Analytics Internship**

**Task 10: Time Series Data Analysis**
