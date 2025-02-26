# Weather Forecasting and Analysis

## Introduction:
This code retrieves current weather data and 5-day forecasts for a specified location using the OpenWeatherMap API. It then analyzes the data, creates interactive visualizations, and predicts future weather conditions using polynomial regression.

## Requirements:
- Python 3.x
- OpenWeatherMap API key
- Required libraries: requests, pandas, numpy, matplotlib, plotly, sklearn

## Code Structure:
The code is divided into several sections:

1. Data Retrieval: Retrieves current weather data and 5-day forecasts for a specified location using the OpenWeatherMap API.
2. Data Preparation: Prepares the retrieved data for analysis and visualization.
3. Data Analysis and Visualization: Creates interactive visualizations of the weather data using Plotly.
4. Weather Prediction: Uses polynomial regression to predict future weather conditions.
5. Results Visualization: Visualizes the predicted weather conditions along with the original forecast data.

## Functions:
- get_weather_data(city_name): Retrieves current weather data for a specified location.
- display_weather_data(weather_data): Displays the retrieved weather data.
- get_weather_forecast(city_name): Retrieves 5-day weather forecasts for a specified location.
- prepare_forecast_data(weather_data): Prepares the retrieved forecast data for analysis and visualization.

## Variables:
- df: Pandas DataFrame containing the retrieved weather data.
- df_all: Pandas DataFrame containing all the retrieved weather data, including forecasts and predicted values.
- X_test: NumPy array containing the input values for prediction.
- y_temp_pred, y_hum_pred, y_pre_pred, y_win_pred: NumPy arrays containing the predicted values.

# Models:
- model: Polynomial regression model used for predicting future weather conditions.

# Visualizations:
- Interactive Plotly graphs displaying the weather data and predicted values.

# Example Use Cases:
- Retrieve current weather data and 5-day forecasts for a specified location.
- Analyze and visualize the retrieved weather data.
- Predict future weather conditions using polynomial regression.
- Visualize the predicted weather conditions along with the original forecast data.
