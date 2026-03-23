# Time Series Analysis: US Consumer Price Index

A comprehensive time series analysis and forecasting project for the US Consumer Price Index (CPI) using statistical modeling and econometric techniques.

## 📊 Project Overview

This project applies rigorous time series methodology to model and forecast the US Consumer Price Index (CPI) monthly data. The analysis includes exploratory data analysis, stationarity testing, model identification, estimation, and out-of-sample forecasting performance evaluation.

## 📁 Project Structure

```
├── CPI.ipynb                    # Main CPI analysis and forecasting
├── notebooks/
│   ├── Inflation.ipynb          # Inflation-related analysis
│   └── UNRATE.ipynb             # Unemployment rate analysis
├── data/
│   ├── cpiai.csv                # CPI data
│   ├── UNRATE.csv               # Unemployment rate data
│   ├── Employement.csv          # Employment data
│   └── VIX.csv                  # Volatility index data
└── Full_Report.pdf              # Comprehensive analysis report
```

## 📈 Methodology

1. **Exploratory Analysis** - Data visualization and variance stabilization using Box-Cox transformation
2. **Stationarity Testing** - ADF test, detrending, and differencing
3. **Model Identification** - ACF/PACF analysis
4. **Model Estimation** - ARMA/ARIMA model selection using AIC/BIC criteria
5. **Residual Diagnostics** - Ljung-Box test, Shapiro-Wilk test, and Runs test
6. **Forecasting** - Out-of-sample performance evaluation

## 📊 Data

- **Source:** US Bureau of Labor Statistics (BLS) via FRED
- **Variable:** CPI Index (all items, not seasonally adjusted)
- **Frequency:** Monthly
- **Training Set:** January 2010 – December 2018 (108 observations)
- **Test Set:** January – December 2019 (12 observations)

_Note: The time period was specifically chosen to avoid external economic shocks (2008 crisis, COVID-19 pandemic)_

## 🛠️ Requirements

- R 4.0+
- R packages:
  - `readr` - Data reading
  - `dplyr` - Data manipulation
  - `ggplot2` - Visualization
  - `forecast` - Time series forecasting
  - `tseries` - Time series analysis
  - `urca` - Unit root tests
  - `lmtest` - Diagnostic tests
  - `randtests` - Randomness tests
  - `nortest` - Normality tests

## 🚀 Quick Start

1. Clone the repository
2. Open `CPI.ipynb` in RStudio or Jupyter
3. Install required packages (first code cell)
4. Run cells sequentially to perform the analysis

## 📝 Key Findings

See `Full_Report.pdf` for detailed findings, visualizations, and forecasting results.

## 👨‍🎓 Author

Guendouz Ahmed Fateh

This project is part of the TSAC module at ENSIA.
