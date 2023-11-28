# Single_Stock_Tracker

Introduction

The Single Stock Tracker is a Python script designed to facilitate the study and comparison of historical stock prices by dynamically converting them to USD. Leveraging the Yahoo Finance API and the yfinance library, this script retrieves historical stock data for a specified ticker symbol over a defined time period. The primary objective is to automate and enhance the analysis of any given stock by providing a versatile tool for historical data analysts and investors.

Data

The script utilizes the Yahoo Finance API through the yfinance library to fetch historical stock data. Users can specify the desired ticker symbol and the time period for which they want to retrieve historical stock prices. The data includes essential information such as Open, High, Low, Close, Volume, and Adjusted Close prices for each trading day within the specified time frame.

Methodology

1. Retrieving Historical Stock Data
The script uses the yfinance library to connect to the Yahoo Finance API and retrieve historical stock data for the specified ticker symbol.
Users can define the time period for which they want to fetch historical stock prices.
2. Currency Conversion
To enable dynamic currency conversion, the script employs the forex-python module.
Real-time exchange rates are obtained based on the source currency, allowing for accurate and up-to-date currency conversion.
3. Adaptability
The program is adaptable, allowing users to display historical data for their desired periods, enhancing flexibility in analyzing stock performance.
4. Stock Analysis for the Last Year
For the last year of historical data, the script provides additional stock analysis features. 
5. Bollinger Bands Analysis
The script calculates and visualizes Bollinger Bands, offering insights into stock volatility and potential trend reversals.
6. Support and Resistance Lines
The script identifies and displays support and resistance lines, aiding in the analysis of potential price levels where a stock may experience buying or selling pressure.
Results

The script generates a Dashboard that summarises the stock and displays certain year-over-year indicators. It also shows the historical statistics for the selected time period, as well as their SMA. The dashboard also features a stock analysis function that displays support and resistance lines as well as the visualisation of Bollinger Bands for insights into stock volatility and potential trend reversals.

Discussions

1. Yahoo Finance API Integration
The use of the Yahoo Finance API and yfinance library ensures reliable and accurate retrieval of historical stock data.
2. Dynamic Currency Conversion
The incorporation of the forex-python module allows users to perform dynamic currency conversion, enhancing the script's versatility.
3. Precision and Flexibility
The script provides a precise and flexible solution for analysts and investors, enabling them to compare historical stock prices across various currencies.
4. Additional Stock Analysis Features
The script extends its functionality by providing Bollinger Bands analysis and support and resistance lines for the last year of historical data.

Conclusion

All in all, the Single Stock Tracker offers a valuable resource for historical data analysts and investors. By automating the retrieval of historical stock data, incorporating dynamic currency conversion, and providing additional stock analysis features, the script empowers users to conduct thorough and insightful analyses of historical stock prices with precision and adaptability.


Example

ticker = 'DOW'
years_back = 5
create_dashboard(ticker, years_back)

<img width="1254" alt="Screenshot 2023-11-27 at 12 54 21" src="https://github.com/glicerio-vergara/Single_Stock_Tracker/assets/79378133/44b5025a-ca8e-4dfb-8610-1bdd491f589d">



