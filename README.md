# Currency Conversion API Request 🌍💱

## Overview
This project analyzes currency exchange rates using the Alpha Vantage API. It aims to explore trends over time, especially in connection to major global events. 📈✨

## Team Members 👥
- Ruben: vielleicht-07

## Approach 🔍
1. **API Data Retrieval**: Fetch weekly exchange rates between chosen currencies using the Alpha Vantage API.
2. **Data Processing**: Clean and manipulate the data for analysis, including calculating averages and percentage changes in currency prices.
3. **Exploratory Data Analysis (EDA)**: Visualize and analyze trends in currency fluctuations over a specific time period.

## Function Dates 📅
- **Analysis Period**: February 24, 2017 - February 24, 2023 (One year since the war began).

## Tools & Technologies 🛠️
- **Python**: Main programming language for data analysis.
- **Requests**: To make API calls for retrieving currency data.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For data visualization.

## Key Insights 💡
- Analyze how exchange rates fluctuate in response to global events.
- Identify significant trends and understand the impact of these changes on various currencies.

## Analysis Details 📊
- **Open-to-Close Average Analysis**: From February 2017 to February 2023.
- **Examination of Price Fluctuations**: During major global events.

## Hypothesis 🤔
We believe that during the Russia-Ukraine war, the Euro (EUR) has shown the least fluctuation, while the Chinese Yuan (CNY) has gained the most value. We will verify this using data from the Alpha Vantage API.

### Currency List 💵
- Euro (EUR)
- Russian Ruble (RUB)
- Ukrainian Hryvnia (UAH)
- Chinese Yuan (CNY)

### Why Use the US Dollar 🇺🇸
- **Stability**: Main global reserve currency.
- **Liquidity**: Used in most international transactions.
- **Confidence**: Effective monetary policy by the Federal Reserve.
- **Resilience**: Holds its value during crises.

## Currency Fluctuations During the Russia-Ukraine Conflict 📉
- **Base Price**: February 20, 2022 (the start of the war).
- **Calculation**: Percentage change for each currency using the average of their opening and closing prices compared to the base price.
- **Result**: Median fluctuations over the first year:
  - EUR: 2.76% 📈
  - RUB: 17.49% 📉
  - CNY: 3.42% 📈
  - UAH: 20.0% 📉

### Simple Moving Average (SMA) 📏
We use the Simple Moving Average (SMA) to smooth out price fluctuations and identify long-term trends, minimizing sharp variations.

## References 🔗
- [Alpha Vantage API Documentation](https://www.alphavantage.co/documentation/)
- [Bullion Rates - Currency Fluctuations](https://www.bullion-rates.com)
