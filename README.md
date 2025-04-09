📈 Stock Price Tracker with Python
A Python script that fetches and visualizes historical stock prices, moving averages, and price alerts using Yahoo Finance (yfinance).

Stock Price Tracker Example (Example plot for AAPL stock)

🚀 Features
Fetch historical stock data for any ticker (e.g., AAPL, TSLA, BTC-USD)

Plot closing prices with customizable date ranges

Calculate & visualize moving averages (20-day and 50-day MA)

Price alert system – Get notified if the stock crosses a user-defined threshold

Google Colab ready – Run directly in the cloud with no setup required

📦 Installation
Run in Google Colab (Recommended)
Open In Colab

Click the Open in Colab button above.

Modify the ticker, dates, or alert price in the "User Inputs" section.

Run all cells (Runtime > Run all).

📚 How It Works
Data Fetching: Uses the yfinance library to download stock data from Yahoo Finance.

Moving Averages: Computes rolling averages to identify trends.

Visualization: Generates plots using matplotlib.

Alert System: Checks if the latest closing price crosses the user-defined threshold.

🌟 Extend This Project
Compare multiple stocks

Add more technical indicators (RSI, Bollinger Bands)

Convert to a real-time dashboard with Streamlit

📜 License
This project is licensed under the MIT License.

🙌 Credits
Data provided by Yahoo Finance

Built with Python libraries: yfinance, matplotlib, pandas
