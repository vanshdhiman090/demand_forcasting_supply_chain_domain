# Walmart Weekly Sales Forecasting

# Project Overview
This project forecasts weekly sales for 45 Walmart stores using historical sales and economic indicators. Accurate demand forecasting helps reduce stockouts, avoid overstock, and support inventory planning.

# Dataset
Columns used:
Store, Date, Weekly_Sales, Holiday_Flag, Temperature, Fuel_Price, CPI, Unemployment

# Methodology

Data Preprocessing & EDA: Handled missing values, created lag/rolling features, added holiday indicators.

Models Tested: Naive Forecast, Moving Average, ARIMA, Multiple Linear Regression, Prophet.

Evaluation: Walk-forward validation using MAE and MAPE.

# Model Comparison — Store 1

Model	MAE	MAPE (%)	Summary
Naive	106,663	6.64	Baseline
Moving Average	106,082	6.60	Slight improvement
ARIMA	111,887	6.92	Captures short-term trends
Linear Regression	117,981	7.07	Struggles with seasonality
Prophet	76,179	4.80	 Best — captures trend, seasonality & holidays

# Key Insights

Prophet significantly outperforms other models, effectively capturing seasonal and holiday effects.

Weekly sales are influenced by store-specific trends, holidays, and economic indicators.

# Tools & Technologies
Python (pandas, scikit-learn, statsmodels, Prophet), matplotlib, plotly, Git

# Deliverables

Reproducible Google coolab notebook 

Forecast comparison CSV

Visualizations of actual vs predicted sales

Future Work

Explore hierarchical forecasting (store & SKU level)

Incorporate additional external factors (weather, promotions, macroeconomic indicators)

