# Stock Analysis Dashboard

This project aims to provide an interactive dashboard for analyzing stock data using Tableau. The dashboard includes various visualizations and metrics to help users understand the performance of different stocks over time and compare them to the broader market.

## Features

- **Stock Data Extraction:** The Python script fetches one year historical stock data for companies listed in the S&P 500 index from Yahoo Finance using the `yfinance` library.

- **Data Analysis Metrics:** The dashboard provides key metrics such as starting date, starting Price, ending date, ending Price, highest price and lowest price in the selected period, along with total earnings in both dollar ($) and percentage (%) values.

- **Tableau Dashboard:** The dashboard consists of several interactive visualizations, including:
  - Candlestick charts displaying the stock trend with opening, closing, highest, and lowest prices.
  - Time series plots illustrating daily stock prices and trading volumes.
  - Comparison of stock price trends with the S&P 500 index.
  - Price difference between daily opening and closing price.
  - Top gainers and losers based on the end date.



- **Tableau Cloud:** https://public.tableau.com/app/profile/mukesh.seerapu/viz/StockAnalysis-04_04_2024/StockAnalysis?publish=yes

 <img width="947" alt="image" src="https://github.com/seerapumukesh/Stock_Analysis/assets/98502336/a56530dd-3ee8-4f21-a496-4176914667c5">



## Usage

1. **Data Collection:** Run the provided Python script to extract historical stock data and save it in an Excel file.

2. **Tableau Dashboard:** Open the Tableau workbook file to explore the visualizations and metrics. Users can interact with the dashboard to filter data based on their preferences and analyze specific stocks or time periods.

## Requirements

- Python 3.x
- `yfinance` library
- Tableau Desktop or Tableau Public
