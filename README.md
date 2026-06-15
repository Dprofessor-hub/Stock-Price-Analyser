# 📈 Stock Price Analyser

## Application Preview

<img width="1901" height="996" alt="Application Preview" src="https://github.com/user-attachments/assets/eefdb5d6-a0ee-439f-8c6a-35c8057ba718" />

## Application Output

<img width="1893" height="997" alt="Application Output" src="https://github.com/user-attachments/assets/21120cbb-965f-440b-a7bc-65202c76151c" />


## Overview

This project is a simple Stock Price Analyser built using Python. It allows users to enter a stock symbol and instantly view basic stock information along with a price trend chart.

The application fetches real-time market data and displays historical stock performance in an easy-to-understand visual format.

## Features

* Search any stock using its symbol
* Supports Indian stocks (using `.NS`) and international stocks
* Displays:

  * Company name
  * Current stock price
  * Previous closing price comparison
  * Percentage change in price
* Generates a stock price chart
* Shows:

  * Daily closing prices
  * 7-Day Moving Average
  * 30-Day Moving Average
 
## Stock Analysis Output

<img width="1322" height="740" alt="Stock price analyzer chart" src="https://github.com/user-attachments/assets/80ad13a0-bc21-4972-9b0b-33adbd66ad5e" />


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Yahoo Finance (yFinance)

## How to Run

1. Install the required library:

   ```
   pip install yfinance
   ```

2. Run the notebook.

3. Enter a stock symbol when prompted.
   Examples:

   * `AAPL` (Apple)
   * `MSFT` (Microsoft)
   * `RELIANCE.NS` (Reliance Industries)

4. View the stock details and analysis chart.

## Example Output

The analyser provides:

* Company information
* Current market price
* Price change percentage
* Historical stock performance graph with moving averages

## Purpose

This project was created to help users quickly analyze stock performance and understand market trends through simple visualizations.
