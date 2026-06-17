# Brent Crude Oil Price Forecasting and Market Analysis

## Project Overview

This project analyses and forecasts Brent crude oil prices using financial market data and machine learning techniques. It was developed as part of a data science assessment and demonstrates an end-to-end workflow covering data collection, exploratory data analysis, feature engineering, forecasting models, and model evaluation.

The project is divided into two stages:

* **Stage 1:** Data collection, cleaning, merging, and exploratory data analysis
* **Stage 2:** Time-series feature engineering, forecasting model development, and performance evaluation

## Business Problem

Brent crude oil is one of the most important global commodities, and its price movement is influenced by market volatility, currency strength, equity market behaviour, and investor sentiment. Forecasting crude oil prices can support better decision-making in energy markets, financial analysis, risk management, and business planning.

The aim of this project is to analyse historical Brent crude oil price behaviour and build forecasting models to predict future price movements.

## Data Sources

The dataset was created using financial market data collected through `yfinance`. The project includes the following market indicators:

* Brent Crude Oil
* Gold
* USD Index
* S&P 500
* VIX Volatility Index

Stage 1 collects and prepares the cleaned merged dataset, which is then used in Stage 2 for forecasting.

## Project Workflow

### Stage 1: Data Collection and Exploratory Analysis

The first notebook focuses on collecting and preparing financial market data. It includes:

* Data collection using `yfinance`
* Data cleaning and formatting
* Merging multiple market indicators into one dataset
* Missing value and duplicate checks
* Trend analysis of Brent crude oil prices
* Normalised comparison with other financial indicators
* Moving average analysis
* Monthly trend analysis
* Correlation analysis between Brent oil and market indicators

### Stage 2: Time-Series Forecasting

The second notebook focuses on forecasting Brent crude oil prices using machine learning and time-series feature engineering. It includes:

* Stationarity testing using the Augmented Dickey-Fuller test
* Time-series feature engineering
* Lag features
* Daily returns
* Rolling averages
* Rolling volatility
* RSI indicator
* Bollinger Band width
* MACD-related indicators
* Calendar-based features
* Chronological train-validation-test split
* Model training and comparison
* Forecast evaluation and visualisation

## Models Used

The forecasting stage compares multiple models, including:

* Naive Persistence Model
* Ridge Regression
* Random Forest
* XGBoost / Gradient Boosting model

## Evaluation Metrics

The models are evaluated using:

* MAE
* RMSE
* MAPE
* R² Score
* Directional Accuracy
* Bootstrap confidence intervals

## Key Skills Demonstrated

* Python programming
* Financial data analysis
* Time-series analysis
* Data cleaning and preprocessing
* Exploratory data analysis
* Feature engineering
* Machine learning model comparison
* Forecast evaluation
* Data visualisation
* Business problem framing

## Repository Structure

```text
brent-crude-oil-forecasting-and-market-analysis/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   ├── 01_data_collection_and_exploratory_analysis.ipynb
│   └── 02_time_series_forecasting_models.ipynb
│
├── data/
│   └── README.md
│
└── figures/
    └── project_visualisations.png
```

## How to Run

The notebooks were originally developed in Google Colab as part of an assessment. To run the project:

1. Open the notebooks in Google Colab or Jupyter Notebook.
2. Run Stage 1 to collect and clean the financial market data.
3. Use the cleaned dataset generated from Stage 1 in Stage 2.
4. Run Stage 2 to train forecasting models and evaluate performance.

Note: The Stage 2 notebook may require the dataset path to match the user’s local or Google Drive directory.

## Project Outcome

This project demonstrates how financial time-series data can be collected, analysed, and used to build machine learning forecasting models. The analysis provides insights into Brent crude oil price behaviour and evaluates different modelling approaches for short-term price forecasting.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* yFinance
* Scikit-learn
* XGBoost
* Statsmodels

## Author

Prajval J S
