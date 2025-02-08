# Stock Portfolio Optimization

## Project Overview

This project aims to optimize a stock portfolio by selecting high-performing stocks from the S&P 500, ensuring diversity across various industries. It involves extracting and analyzing stock data, conducting equity research, performing financial analysis, and optimizing portfolio risk and return.

## Key Features

- **Diverse Stock Selection**: Identified four high-performing stocks from the S&P 500, ensuring a diverse representation across various industries and analyzing their correlation.
- **Data Extraction**: Extracted stock data using the Yfinance library in Python for precise and up-to-date information.
- **Equity Research**: Conducted comprehensive equity research through SWOT analysis, industry analysis, and company-specific evaluations to gauge stock performance.
- **Financial Analysis**: Performed in-depth financial analysis and Monte Carlo simulations to quantitatively measure company performance.
- **Portfolio Optimization**: Optimized two tailored portfolio versions, high- and low-risk, based on volatility and expected returns.
- **Risk Assessment**: Developed a Capital Asset Pricing Model (CAPM) using Python to understand the relationship between each stock in the portfolio and the market, enhancing risk assessment and portfolio optimization.

## Technologies Used

**Programming Languages**: Python  
**Libraries**: Yfinance, Pandas, NumPy, Matplotlib, Scikit-learn, Statsmodels  
**Tools**: Jupyter Notebooks

## Data Extraction

The stock data is extracted using the **Yfinance** library, which provides precise and up-to-date information from the S&P 500 companies. The data includes historical stock prices, dividends, and other relevant financial data.

## Data Preprocessing

Python and Pandas are used to clean and preprocess the extracted stock data, including:
- Handling missing data and null values.
- Calculating returns, volatility, and correlations between selected stocks.
- Preparing data for financial analysis and optimization models.

## Financial Analysis

An in-depth financial analysis was performed that included:
- SWOT analysis: To assess strengths, weaknesses, opportunities, and threats of the selected companies.
- Monte Carlo simulations: To simulate different portfolio outcomes and estimate risk and return.
- Financial ratios: Such as Price-to-Earnings (P/E), Price-to-Book (P/B), and others to evaluate company performance.

## Portfolio Optimization

Two tailored portfolio versions were optimized:
- **High-risk portfolio**: Focused on high volatility stocks with potentially higher returns.
- **Low-risk portfolio**: Focused on stable stocks with lower volatility but more consistent returns.
The optimization was done using modern portfolio theory to maximize expected returns based on risk tolerance.

## Risk Assessment

A **Capital Asset Pricing Model (CAPM)** was developed to assess the relationship between each stock’s risk and the overall market. This model helped in understanding the risk-adjusted returns for each stock and the portfolio as a whole.

## How to Use the Project

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook `portfolio_optimization.ipynb` to see the analysis and optimization steps.
4. You can modify the stock selection or optimization parameters to explore different portfolio configurations.

## Project Structure

- **portfolio_optimization.ipynb**: Jupyter notebook with the entire stock portfolio optimization process.
- **requirements.txt**: List of Python dependencies for the project.
- **README.md**: You're here!
- **data_analysis.py**: Python script containing the analysis and calculations for the portfolio.
  
## Contributing

If you're interested in collaborating on this project, feel free to reach out and discuss potential contributions.

## License

This project is open-source under the JettawatV license. You can use and modify the code as needed.

## Contact Information

You can reach out to Jettawatvd@gmail.com for questions, collaboration, or more information about this project.
