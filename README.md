Trading Calculator App
Overview
This is a web-based trading calculator application that helps users analyze cryptocurrency trading scenarios. It allows users to select an exchange, a coin, input trading parameters, view price charts, and calculate profits or losses, including fees and liquidation risks.
Features

Exchange and Coin Selection: Choose from exchanges (Binance, OKX, Bybit, Gate.io) and select a coin from the top 100 by market cap (data from CoinGecko).
Price Chart: View historical price data for the selected coin within a specified date range.
Trade Calculation: Calculate profits, trading fees, funding fees, and check for liquidation risks based on input parameters (entry price, take profit, capital, leverage, position).
Support for PI on OKX: Automatically adjusts date range for PI coin on OKX if the entry date is before its listing date (22/12/2023).

Usage

Access the application via the GitHub Pages URL: https://nivinz.github.io/fc/
Select an exchange and a coin.
Input the entry and exit dates, entry price, take profit price, capital, leverage, and position (Long/Short).
Click "View Chart" to see the price chart.
Click "Calculate" to compute the trading results.

Technologies Used

HTML/CSS/JavaScript: Core web technologies.
Bootstrap: For responsive design.
Chart.js: For rendering price charts.
Flatpickr: For date picker functionality.
CoinGecko API: For market cap data.
Exchange APIs: Binance, OKX, Bybit, and Gate.io APIs for historical price data.

Notes

Ensure a stable internet connection as the app relies on external APIs.
The app is a static web application hosted on GitHub Pages, so no backend or data storage is involved.

License
This project is open-source and available under the MIT License. Feel free to fork and contribute!
