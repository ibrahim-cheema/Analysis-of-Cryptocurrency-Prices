# Analysis-of-Cryptocurrency-Prices
This project uses the Kraken API to fetch and analyze historical price data for Bitcoin, Ripple, and Ethereum. The CryptoData class cleans the data, computes key metrics like mean returns, and visualizes price trends. Results are saved as CSV files and summarized in an Excel sheet, offering insights into cryptocurrency performance.



## Features
- Fetches historical price data from the Kraken API.
- Cleans and structures the data for analysis.
- Computes statistical metrics (mean, median, standard deviation of returns).
- Identifies the date with the highest return.
- Visualizes historical prices and mean returns using Matplotlib.
- Saves cleaned data and analysis results to CSV files and an Excel summary.

## Installation
Make sure you have Python installed along with the following libraries:
- `requests`
- `pandas`
- `numpy`
- `matplotlib`
- `openpyxl` (for saving Excel files)
