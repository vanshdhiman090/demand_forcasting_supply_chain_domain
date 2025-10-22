# Project: Store-Level Demand Forecasting for Walmart
# Objective
The primary objective of this project is to develop an accurate weekly sales forecast for a single Walmart store. In retail, inaccurate demand forecasting leads to significant operational challenges. Stockouts result in lost sales and decreased customer satisfaction, while overstocking ties up capital in unsold inventory, increases storage costs, and can lead to markdowns that erode profit margins.
This project addresses this challenge by building and comparing several forecasting models. The goal is to identify a model that provides a more reliable prediction than a simple baseline, enabling smarter inventory planning and supporting the key business goals of cost reduction and improved profitability.
# Methodology
Five distinct time-series forecasting models were developed and compared to find the most accurate approach:
Naive Forecast (Baseline)
Moving Average
ARIMA
Multiple Linear Regression
Prophet
Each model's performance was rigorously evaluated using walk-forward validation. The primary metrics for comparing accuracy were Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE).
# Key Result & Business Takeaway
The Prophet model proved to be the most effective, significantly outperforming all other models tested. It reduced the forecast error (MAPE) by over 27% compared to the naive baseline.
This result demonstrates that implementing a sophisticated model like Prophet can dramatically enhance forecasting precision. Adopting this model for weekly planning would lead to more effective inventory management, reducing the financial impact of both stockouts and overstock and thereby improving the store's bottom line.
# Tools & Technologies
Languages: Python
Libraries: pandas, scikit-learn, statsmodels, Prophet , matplotlib 
Visualization: matplotlib, plotly
