# BearBullBuddy - Your Stock Analysis Assistant

check it out [here](https://www.bullbearbuddy.com/)

## Overview
BearBullBuddy is a Streamlit application that provides real-time stock information, technical indicators, and visualizations. It integrates the OpenAI API for natural language interactions, the Yahoo Finance API for up-to-date stock data, along with various libraries such as Matplotlib for graph visualizations, and Pandas for data manipulation. 

## Current Features
• Retrieve the latest stock price for a given company.

• Calculate and display Simple Moving Averages (SMA) and Exponential Moving Averages (EMA) for a stock.

• Calculate and display the Relative Strength Index (RSI) for a stock.

• Calculate and display the Moving Average Convergence Divergence (MACD) for a stock.

• Generate a plot of the stock price over the last year.

• Utilize OpenAI's GPT-3 to interactively communicate with the assistant.

## Usage

1. Install the required Python libraries using the following command:

    ```
    pip install openai pandas matplotlib streamlit yfinance
    ```
    
3. Set up your OpenAI API key by creating a file named `API_KEY` and placing your API key inside it.

4. Run the `StockAssistant.py` script using the following command:

    ```
    streamlit run StockAssistant.py
    ```
   
## Visuals
![exmple1](https://github.com/xMarkGergis/Stock-Assistant/assets/121286835/b89c2998-3b02-45ff-aa05-2147e9c0d622)
![exmple2](https://github.com/xMarkGergis/Stock-Assistant/assets/121286835/cfdb8bf2-3b78-4f15-bd1b-6e6cc26512ab)
