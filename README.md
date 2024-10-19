# Currency Conversion API Request 🌍💱

## Overview
The Currency Conversion API Request project aims to analyze currency exchange rates using the Alpha Vantage API. By examining currency fluctuations, this project will help understand trends over time, particularly in relation to significant global events. 📈✨

## Team Members 👥
- Ruben: vielleicht-07

## Approach 🔍
1. **API Data Retrieval**: Fetch weekly currency exchange rates between specified currencies using the Alpha Vantage API.
2. **Data Processing**: Clean and manipulate the data for analysis, including calculating averages and percentage variations in currency prices.
3. **Exploratory Data Analysis (EDA)**: Visualize and analyze trends in currency fluctuations over a specific time period.

## Function Dates 📅
- **Analysis Period**: February 24, 2017 - February 24, 2023 (One Year Since the War Began)

## Tools & Technologies 🛠️
- **Python**: The primary programming language used for data analysis.
- **Requests**: For making API calls to retrieve currency data.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For data visualization.

## Key Insights 💡
- Analyze how currency exchange rates fluctuate in response to global events.
- Identify significant trends and provide insights on the impact of these changes on various currencies.

## Analysis Details 📊
- **Open-to-Close Average Analysis**: From February 2017 to February 2023.
- **Examination of Price Fluctuations**: During significant global events.

## Hypothesis 🤔
We believe that during the war between Russia and Ukraine, the currency that has shown less fluctuation is the EUR (Euro), while the currency that has gained the most value is the CNY (Chinese Yuan). We will verify this hypothesis by obtaining data from the Alpha Vantage API.

### Currency List 💵
- Euro (EUR)
- Russian Ruble (RUB)
- Ukrainian Hryvnia (UAH)
- Chinese Yuan (CNY)

### Reasons for Using the US Dollar 🇺🇸
- **Stability**: Main reserve currency.
- **Liquidity**: Used in most international transactions.
- **Confidence**: Effective monetary policy by the Federal Reserve.
- **Resilience**: Maintains its value during crises.

## Analysis of Currency Fluctuations During the Russia-Ukraine Conflict 📉
- **Base Price**: February 20, 2022 (currency value at the start of the war).
- **Calculation**: Percentage change for each currency using the average of their opening and closing prices relative to the base price.
- **Result**: Median fluctuations over the first year:
  - EUR: 2.76% 📈
  - RUB: 17.49% 📉
  - CNY: 3.42% 📈
  - UAH: 20.0% 📉

### Simple Moving Average (SMA) 📏
We use the Simple Moving Average (SMA) to smooth out price fluctuations, allowing us to identify long-term trends and minimize the impact of sharp variations.


## References 🔗
- [Alpha Vantage API Documentation](https://www.alphavantage.co/documentation/)
- [Bullion Rates - Currency Fluctuations](https://www.bullion-rates.com)
