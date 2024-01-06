# Stock Market Performance Analysis

## Overview
This project aims to analyze and visualize the stock market performance of some of the largest tech companies over the last three months. By leveraging financial data from Yahoo Finance, this analysis includes stock price trends, moving averages, volatility, and price correlations.

## Dependencies
This project relies on the following Python libraries:
- Pandas: For data manipulation and analysis.
- yfinance: For downloading historical market data from Yahoo Finance.
- Plotly: For creating interactive charts and visualizations.

To install these libraries, run the following command:
`pip install pandas yfinance plotly`

## Data
The data for this project is sourced in real-time from Yahoo Finance, focusing on four major tech companies: Apple (AAPL), Microsoft (MSFT), Netflix (NFLX), and Google (GOOG).

## Preprocessing
The preprocessing stage involves fetching stock data for the past three months and consolidating it into a single DataFrame with 'Date' and 'Ticker' as multi-level indices to organize the data effectively.

## Model Training and Evaluation
This project does not involve a predictive model but rather a descriptive analysis using various data visualization techniques.

## Usage
To replicate this analysis:

1. Ensure all dependencies are installed using the provided pip command.
2. Execute the script to fetch the latest data and generate the visualizations.
3. The tickers list can be modified to analyze different stocks, or the date range can be altered to focus on a different period.

## Results
The script generates several visualizations, which include:

1. Line and area charts displaying the stock prices over the last three months.
2. Moving averages (10-day and 20-day) to identify potential bullish or bearish trends.
3. Volatility trends to highlight the stability of the stock prices.
4. Scatter plots to exhibit the correlation between the stock prices of pairs of companies.
5. These visualizations provide valuable insights into market trends and can help in making informed investment decisions.


