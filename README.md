# Analysis-of-Cryptocurrency-Prices
This project uses the Kraken API to fetch and analyze historical price data for Bitcoin, Ripple, and Ethereum. The CryptoData class cleans the data, computes key metrics like mean returns, and visualizes price trends. Results are saved as CSV files and summarized in an Excel sheet, offering insights into cryptocurrency performance.

## Project Focus
This project was developed without the use of high-level languages to emphasize object-oriented programming (OOP) concepts and the basics of Python. The goal is to provide a clear understanding of these foundational principles, making it easier for learners to grasp the core concepts of programming and data analysis.

## Requirements
1. **Scraping Data**: Utilize the `requests` library to fetch HTML content and `BeautifulSoup` for parsing to obtain historical prices for Bitcoin, Ethereum, and Ripple.
2. **Data Cleaning and Structuring**: Implement a `CryptoData` class to manage each cryptocurrency's data, including attributes and methods for cleaning and structuring.
3. **Handling Missing Values**: Address any missing values in the data using strategies like interpolation or filling with the mean.
4. **Data Transformation**: Use NumPy to convert price data into logarithmic returns for each cryptocurrency.
5. **Analysis**: 
   - Calculate mean, median, and standard deviation of returns.
   - Identify the date with the highest return for each cryptocurrency.
   - Determine the correlation matrix between the returns of Bitcoin, Ethereum, and Ripple.
6. **Visualization**: 
   - Create line charts to show historical prices.
   - Generate a bar chart to compare mean returns.
7. **Save Results**: Save cleaned and transformed data along with analysis results in CSV files.
8. **Summarize Findings**: Provide a brief summary of findings, including market trends and notable events.
9. **OOP Concepts**: Ensure adherence to OOP principles, utilizing encapsulation, inheritance, and polymorphism where appropriate.


## Installation
Make sure you have Python installed along with the following libraries:
- `requests`
- `pandas`
- `numpy`
- `matplotlib`
- `openpyxl` (for saving Excel files)
