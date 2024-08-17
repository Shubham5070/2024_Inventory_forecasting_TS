# Time Series Forecasting Project

## Project Overview
This project focuses on time series forecasting by analyzing and modeling a dataset to make accurate predictions. The project includes data preprocessing, stationarity tests, seasonal decomposition, and applying various forecasting models. The primary goal was to deliver effective predictions using different models, with a particular focus on SARIMA and FBProphet.

## Features
- **Data Preprocessing**: Performed data cleaning and preparation to ensure the dataset was ready for analysis.
- **Stationarity Tests**: Utilized Augmented Dickey-Fuller (ADF) and KPSS tests to assess the stationarity of the time series.
- **Seasonal Decomposition**: Conducted seasonal decomposition to analyze the trend, seasonality, and residual components.
- **Transformation**: Applied Box-Cox transformation to address nonstationarity in the time series.
- **Forecasting Models**: Implemented multiple forecasting models, including:
  - **Holt’s Winter**
  - **ARIMA**
  - **SARIMA**
  - **FBProphet**

## Results
- **SARIMA**:
  - RMSE: 3.87
  - MAPE: 5.91
- **FBProphet**:
  - RMSE: 3.65
  - MAPE: 7.26

## File in the Repository
- **Timeseries_project.ipynb**: The Jupyter Notebook containing all the code, analysis, and model implementations for the time series forecasting project.

## Getting Started
### Prerequisites
- **Python 3.x**: Required to run the Jupyter Notebook.
- **Jupyter Notebook**: Required to open and execute the `.ipynb` file.
- **Required Libraries**:
  - pandas
  - numpy
  - statsmodels
  - matplotlib
  - seaborn
  - fbprophet (prophet)
  - scipy

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/timeseries-forecasting.git

