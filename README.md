# Investigate-and-analyze-price-data
Natural Gas Price Estimation
Overview

This Python script is designed to estimate the purchase price of natural gas at any given date based on historical monthly price data. Additionally, it provides an extrapolation for the estimated price one year into the future. The code performs the following tasks:

    Data Loading: It loads monthly natural gas price data from a CSV file containing dates and corresponding prices.

    Data Analysis and Visualization: The code analyzes the historical price data to identify trends, patterns, and factors affecting natural gas prices. It visualizes the data using Matplotlib to provide insights into price fluctuations over time.

    Price Estimation: The script defines a function estimate_price(date) that takes a date as input and returns an estimate of the purchase price of gas at that date. It also extrapolates the price for one year into the future based on historical price trends.

Problem Statement

The code addresses the following problem:

    Data Source: The current process involves taking a monthly snapshot of prices from a market data provider, representing the market price of natural gas delivered at the end of each calendar month.

    Client Needs: The client may require an indicative price for a longer-term storage contract beyond the available historical data.

Dependencies

The script requires the following dependencies:

    Python 3.x
    pandas
    NumPy
    Matplotlib

Usage

    Ensure that Python and the required dependencies are installed on your system.
    Download the provided CSV file containing the monthly natural gas price data.
    Update the file path of the CSV file in the script if necessary.
    Run the Python script.
    Provide a date for which you want to estimate the natural gas price.
    The script will display the estimated price for the given date and the extrapolated price for one year into the future.

Contributions

Contributions to enhance the code, improve functionality, or fix issues are welcome. Please feel free to submit pull requests or raise issues if you encounter any problems or have suggestions for improvement.
Disclaimer

This script provides estimated natural gas prices based on historical data and extrapolation. Actual market prices may vary due to various factors such as market conditions, supply and demand dynamics, geopolitical events, and regulatory changes. Users should exercise caution and verify the estimated prices before making any decisions based on the provided estimates.
