# Streamlit Stock Forecast App

## Overview

The Streamlit Stock Forecast App is a web-based application built using Streamlit, yfinance, and Facebook's Prophet library in Python. This application enables users to forecast stock prices for selected companies by leveraging historical stock data.

## Functionalities

### 1. Stock Selection
- Users can choose from a selection of well-known stocks such as Google (GOOG), Apple (AAPL), Microsoft (MSFT), and Meta Platforms Inc. (META) using a dropdown menu.

### 2. Prediction Period Selection
- A slider allows users to select the number of years they wish to forecast the stock prices for.
  ![image](https://github.com/ParmeetChanne/Stock-Prediction-Streamlit/assets/67189839/1063cfff-a41b-43d7-9feb-c904a75de355)


### 3. Data Visualization
- The app displays the raw historical stock data for the selected stock, presenting the 'Open' and 'Close' values over time.
  ![image](https://github.com/ParmeetChanne/Stock-Prediction-Streamlit/assets/67189839/8b5f0667-c875-4f1f-a23c-1c864422adc4)


### 4. Stock Price Forecasting
- Utilizing the Prophet library, the app trains a forecasting model on the historical stock data and generates future predictions for the selected stock's closing prices.

### 5. Forecast Visualizations
- Users can view the forecasted stock prices for the chosen number of years, presented in an interactive Plotly chart, displaying the predicted trend.
  ![image](https://github.com/ParmeetChanne/Stock-Prediction-Streamlit/assets/67189839/40ac1d37-d129-405c-8476-8a3622da30ff)
  ![image](https://github.com/ParmeetChanne/Stock-Prediction-Streamlit/assets/67189839/39a3413d-a6d3-4a48-8e18-358cda0358df)



### 6. Forecast Components
- The application showcases the individual components contributing to the forecast, enabling users to analyze the trend and seasonal patterns.

## Usage

1. **Stock Selection**: Choose a stock from the available options in the dropdown menu.
2. **Years of Prediction**: Adjust the slider to select the number of years for forecasting.
3. **Data Visualization**: View the raw historical stock data and observe the trends in 'Open' and 'Close' values over time.
4. **Forecast**: Analyze the generated forecast plot depicting the predicted stock prices for the selected period.
5. **Forecast Components**: Explore the various components contributing to the forecasted stock prices.

## Acknowledgments

The app utilizes yfinance for data retrieval, Prophet for time-series forecasting, and Streamlit for web application development.

## How to Run the App

1. Install the required libraries: `streamlit`, `yfinance`, `prophet`, `plotly`. You can use `!pip install streamlit finance prophet plotly`
2. Execute the code in a Python environment supporting Streamlit.
3. Run the Streamlit app using `streamlit run app_name.py` command in the terminal.

## Disclaimer

The predictions made by this application are based on historical data and do not guarantee future stock prices. It is intended for educational and demonstrational purposes only.
