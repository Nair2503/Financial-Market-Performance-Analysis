# Financial Market Performance Analysis

## Project Overview

This project analyzes the historical performance of major Indian market indices using financial and statistical analysis techniques.

The analysis focuses on historical returns, volatility, moving averages, risk, drawdowns, correlations, India VIX, and Gold prices.

The project is designed as a descriptive market analytics project for Data Analytics and FinTech applications.

## Objectives

- Analyze historical market index performance
- Calculate daily and annual returns
- Measure market volatility
- Analyze maximum drawdown
- Compare risk and return characteristics
- Study correlations between market indices
- Analyze the relationship between India VIX and NIFTY 50
- Analyze the relationship between Gold and NIFTY 50
- Apply statistical tests to identify significant differences
- Generate data-driven insights using visualizations

## Dataset

The project uses historical data for 10 Indian market indices:

- NIFTY 50
- NIFTY Bank
- NIFTY IT
- NIFTY Auto
- NIFTY Pharma
- NIFTY FMCG
- NIFTY Energy
- NIFTY Metal
- NIFTY Midcap 100
- NIFTY Next 50

Additional datasets:

- India VIX historical data
- Gold price in INR

The market-index data covers different historical periods depending on the availability of each index.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab
- GitHub

## Methodology

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Historical Price Analysis
5. Daily Return Calculation
6. Annual Return Analysis
7. Volatility Analysis
8. Moving Average Analysis
9. Risk-Return Analysis
10. Maximum Drawdown Analysis
11. Correlation Analysis
12. India VIX Analysis
13. Gold vs NIFTY 50 Analysis
14. Statistical Testing
15. Insights and Conclusions

## Statistical Analysis

The project uses statistical testing to examine whether differences observed in the historical data are statistically significant.

### One-Way ANOVA

ANOVA was applied to compare mean daily returns across the 10 market indices.

Result:

- F-statistic: 0.7638
- p-value: 0.6502

At a 5% significance level, the analysis did not detect a statistically significant difference among the mean daily returns.

### Gold vs NIFTY 50

A Welch independent t-test was used to compare the mean daily returns.

Result:

- t-statistic: -1.6990
- p-value: 0.0895

At a 5% significance level, the analysis did not detect a statistically significant difference in mean daily returns.

## Key Analysis Areas

### Returns

Daily and annual returns were calculated to understand historical performance patterns.

### Volatility

Daily volatility and annualized volatility were calculated using the standard deviation of daily returns.

### Maximum Drawdown

Maximum drawdown was calculated to measure the largest historical decline from a previous peak.

### Correlation

Correlation analysis was performed using daily returns across the market indices.

### India VIX

India VIX was analyzed alongside NIFTY 50 daily returns.

### Gold

Gold price movements were compared with NIFTY 50 daily returns to examine their historical relationship.

## Visualizations

The project includes:

- Historical Price Comparison
- Normalized Performance
- Annual Returns
- Correlation Heatmap
- Annualized Volatility
- Maximum Drawdown
- Moving Averages
- India VIX
- Gold vs NIFTY 50
- Risk-Return Analysis

## Project Structure

Financial-Market-Performance-Analysis/

    data/
        financial_market_master.csv
        VIX_History.csv
        Gold_price_INR.csv

    results/
        final_market_performance_summary.csv
        project_insights.csv
        risk_summary.csv
        correlation_matrix.csv
        annual_returns.csv
        anova_results.csv

    visualizations/
        historical_prices.png
        normalized_performance.png
        correlation_heatmap.png
        annualized_volatility.png
        maximum_drawdown.png
        moving_average.png
        india_vix.png
        gold_vs_nifty.png
        risk_return.png

    Financial_Market_Performance_Analysis.ipynb
    README.md
    requirements.txt

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries using:

   pip install -r requirements.txt

3. Open the Jupyter Notebook:

   Financial_Market_Performance_Analysis.ipynb

4. Run the notebook cells sequentially.

## Limitations

- The analysis is based on historical data.
- Different indices have different available date ranges.
- Historical performance does not indicate future market performance.
- The project is intended for analytical and educational purposes rather than investment advice.

## Author

Yug Nair

B.Tech Computer Science and Engineering

SRM Institute of Science and Technology
