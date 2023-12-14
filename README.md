Stock Prediction App
Overview
The Stock Prediction App is a web application developed using Streamlit, a Python library for creating interactive web applications. This app predicts the stock prices of selected companies based on historical data using the Prophet forecasting model.

Features
Stock Selection: Users can choose from a predefined list of stocks, including GOOG, AAPL, MSFT, and GME.

Years of Prediction: Users can adjust the number of years for which they want stock price predictions using a slider.

Interactive Data Loading: The app fetches historical stock data using the Yahoo Finance API and displays loading messages to keep users informed about the data retrieval process.

Visualization of Raw Data: The app provides an interactive plot of the raw stock data, allowing users to analyze Open and Close prices over time.

Prophet Forecasting: The app utilizes the Prophet forecasting model from the prophet library to predict future stock prices.

Forecast Plot: Users can view the predicted stock prices along with a visual representation of the forecast for the selected number of years.

Forecast Components: The app displays the components of the forecast, including trend, seasonality, and holidays.

Getting Started
To run the Stock Prediction App, follow these steps:

Install the required libraries by running:

bash
Copy code
pip install streamlit yfinance prophet plotly
Clone the repository:

bash
Copy code
git clone https://github.com/tomisi/stock_prediction_model.git
Navigate to the project directory:

bash
Copy code
cd stock_prediction_model
Run the Streamlit app:

bash
Copy code
streamlit run app.py
Open the provided URL in your browser to access the Stock Prediction App.

Dependencies
streamlit: 0.90.0
yfinance: 0.1.63
prophet: 1.0.1
plotly: 5.3.1
License
This project is licensed under the MIT License.

Acknowledgments
The app uses the yfinance library to fetch stock data from Yahoo Finance.
The forecasting model is powered by the prophet library developed by Facebook.
