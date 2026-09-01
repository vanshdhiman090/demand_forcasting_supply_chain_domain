# Store-Level Demand Forecasting for Walmart

A time-series forecasting project focused on improving weekly retail sales predictions for inventory and planning decisions.

## Business Problem

Retail teams need reliable demand forecasts to balance two competing risks:

- **Stockouts**, which can lead to lost sales and poor customer experience
- **Overstock**, which ties up working capital and increases storage and markdown risk

This project compares several forecasting approaches to determine which model performs best against a simple baseline.

## Approach

Five forecasting methods were evaluated:

1. Naive forecast — baseline
2. Moving Average
3. ARIMA
4. Multiple Linear Regression
5. Prophet

Model performance was assessed using **walk-forward validation**, with **MAE** and **MAPE** used as the primary evaluation metrics.

## Key Result

The documented analysis found that **Prophet produced the strongest forecast and reduced MAPE by more than 27% compared with the naive baseline**.

This demonstrates why model comparison against a simple baseline matters: a more sophisticated forecasting method is only useful when it produces a measurable improvement on unseen periods.

## Business Relevance

More accurate weekly forecasts can support:

- inventory planning
- replenishment decisions
- stockout and overstock risk management
- operational planning

The project is a portfolio analysis rather than a production forecasting system, so the reported result should be interpreted within the dataset and validation setup used here.

## Tech Stack

- **Python**
- **pandas**
- **scikit-learn**
- **statsmodels**
- **Prophet**
- **Matplotlib**
- **Plotly**

## Repository Contents

- [`demend_forcasting.ipynb`](demend_forcasting.ipynb) — analysis and model comparison notebook
- [`Key insights`](Key%20insights) — written findings
- `Walmart_sales_dataset` — dataset used in the analysis

## Skills Demonstrated

Time-series analysis · Forecast evaluation · Walk-forward validation · Model comparison · Business interpretation · Python analytics
