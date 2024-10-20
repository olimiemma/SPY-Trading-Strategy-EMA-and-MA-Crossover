# SPY Trading Strategy: EMA and MA Crossover

This Jupyter notebook implements and analyzes a simple trading strategy for the SPDR S&P 500 ETF Trust (SPY) using Exponential Moving Average (EMA) and Simple Moving Average (MA) crossovers.

## Overview

The strategy uses weekly price data for SPY and implements the following rules:
- Buy when the 50-day Moving Average crosses above the 21-day Exponential Moving Average
- Sell when the 21-day Exponential Moving Average crosses below the 50-day Moving Average

## Contents

1. Data loading and preprocessing
2. Calculation of 21-day EMA and 50-day MA
3. Visualization of price data with EMA and MA
4. Implementation of the trading strategy
5. Analysis of trade results

## Key Features

- Candlestick chart visualization of SPY weekly prices
- Overlay of 21-day EMA and 50-day MA on the price chart
- Identification of buy and sell signals based on EMA/MA crossovers
- Calculation of individual trade performance (entry/exit times, prices, and profit/loss)
- Overall strategy performance metrics

## Results

The notebook provides:
- A dataframe of all trades executed by the strategy
- Entry and exit dates for each trade
- Profit/Loss calculation for each trade
- Overall strategy performance including total return and number of trades

## Requirements

- Python 3.x
- Pandas
- Numpy
- Plotly

## Usage

1. Ensure you have the required libraries installed
2. Load the SPY weekly price data CSV file
3. Run the cells in order to generate the analysis and results

## Potential Improvements

- Experiment with different EMA and MA periods
- Add additional entry/exit criteria to refine the strategy
- Implement risk management techniques
- Conduct backtesting over different time periods

## Disclaimer

This project is for educational purposes only. The trading strategy presented here is not financial advice and may not be suitable for actual trading without further refinement and risk management.
