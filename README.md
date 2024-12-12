Project Title: Time Series Forecasting with Facebook Prophet

Description:

This project implements a Time Series Forecasting model using Facebook's Prophet library in Python. The model is designed to predict Sunspot activity based on historical data.

Dataset:

The project utilizes three datasets:

Daily Sunspot Data: Contains daily sunspot numbers.
Monthly Mean Sunspot Data: Contains monthly average sunspot numbers.
Yearly Mean Sunspot Data: Contains yearly average sunspot numbers.
Model Implementation:

The model is built using the following steps:

Data Preprocessing:

Load and clean the data.
Handle missing values and outliers.
Determine the time unit (day, month, year) of the dataset.
Model Training:

Initialize the Prophet model with appropriate parameters.
Train the model on the historical data.
Model Prediction:

Make predictions for a specified future period (e.g., 100 days, 6 months, 20 years).
Model Evaluation:

Evaluate the model's performance using metrics like Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and R-squared (R2).
Key Features:

Model Flexibility: The code is designed to handle different time units, making it adaptable to various time series datasets.
Parameter Tuning: The model allows for tuning of parameters like growth type, seasonality, and trend changepoints to optimize performance.
Visualization: The project includes visualizations to help understand the data, model predictions, and evaluation results.
