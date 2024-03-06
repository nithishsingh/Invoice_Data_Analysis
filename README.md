# Invoice Data Analysis Project

This project involves analyzing invoice data for a hypothetical client. The dataset is attached, and several tasks need to be performed to derive insights and make predictions.

## Introduction

The goal of this project is to analyze and make predictions based on the provided invoice data for a hypothetical client. The tasks include data preprocessing, exploratory data analysis, and the implementation of predictive models using machine learning and time series analysis techniques.

## Tasks

### 1. Data Preprocessing

- **Importing Data:** Utilize the attached dataset to load the invoice data.
- **Data Cleaning:** Handle any missing or inconsistent data. Ensure data integrity for accurate analysis.

### 2. Exploratory Data Analysis (EDA)

- **Feature Engineering:** Create relevant features from existing data (e.g., total_amount, amount_due, issue_date, due_date).
- **Visualization:** Use visualizations to understand patterns, trends, and potential correlations within the dataset.

### 3. Model Implementation

#### 3.1 RandomForestRegressor

- **Training:** Train a RandomForestRegressor model to predict future revenue based on relevant features.
- **Evaluation:** Assess the models performance using metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE).

#### 3.2 SARIMAX

- **Time Series Analysis:** Implement a SARIMAX model to capture time-dependent patterns in the revenue realization.
- **Prediction:** Forecast revenue for the next 3 months using the SARIMAX model.

#### 3.3 ARIMA

- **Auto ARIMA:** Use auto_arima to automatically select optimal parameters for an ARIMA model.
- **Prediction:** Predict revenue for the next 3 months using the ARIMA model.

### 4. Model Evaluation

- **Performance Metrics:** Evaluate the performance of each model using relevant metrics.
- **Comparison:** Compare the predictions from different models to determine their effectiveness.

### 5. Visualization

- **Plotting:** Create visualizations to showcase actual vs. predicted revenue values for a clear understanding of model performance.

## Usage

tun requiment file, to install all the neccessary dependencies

`pip install -r requirements.txt`

## Dependencies

```
pandas==1.3.3
numpy==1.21.2
matplotlib==3.4.3
seaborn==0.11.2
dash==1.21.0
plotly==5.3.1
scikit-learn==0.24.2
statsmodels==0.13.0
pmdarima==1.8.3

```


