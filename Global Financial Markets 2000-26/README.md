# Global Financial Markets Dashboard 2000–2026

An interactive BI dashboard built with Tableau Public, analyzing 186,356 rows of global financial market data spanning 25+ years across stocks, commodities, cryptocurrencies, and currencies.

## Live Dashboard
[View on Tableau Public](https://public.tableau.com/views/GlobalFinancialMarkets2000-2026/GlobalFinMrkt2000-26)

## Dataset Overview
| Field | Details |
|---|---|
| Rows | 186,356 |
| Columns | 10 |
| Date Range | Jan 2000 – Apr 2026 |
| Assets | 34 total |
| Asset Types | Stock Index, Commodity, Cryptocurrency, Currency |

## Assets Covered
| Type | Assets |
|---|---|
| Stock Index | S&P500, NASDAQ, DAX, FTSE100, Nikkei225, SENSEX, HSI, KOSPI, Shanghai, NIFTY50 |
| Commodity | Gold, Silver, Crude Oil (WTI), Brent Crude, Natural Gas, Copper, Corn, Wheat |
| Cryptocurrency | Bitcoin, Ethereum, BNB, Ripple, Dogecoin, Cardano, Litecoin, Solana |
| Currency | EUR/USD, GBP/USD, JPY/USD, INR/USD, CNY/USD, AUD/USD, CAD/USD, CHF/USD |

## Data Fields
- date: Trading date
- open / high / low / close: Daily OHLC prices
- volume: Trading volume
- symbol: Ticker symbol
- asset_name: Human-readable name
- asset_type: Category (Stock Index / Commodity / Cryptocurrency / Currency)

## Dashboard Charts
1. Price Trend: Asset price movements over time (line chart)
2. Asset Type Performance: Average closing price by asset type (bar chart)
3. Volatility Analysis: Daily High-Low % spread by asset (bar chart)
4. Trading Volume: Market activity over time with crisis spikes (area chart)
5. Crypto Heatmap: Cryptocurrency prices by year (highlight table)
6. Currency Trends: USD exchange rates 2000-2026 (line chart)

## How to run locally
Open index.html in any browser - no server needed.

## Tech Stack
- Tableau Public (dashboard)
- HTML/CSS (wrapper page)
- GitHub Pages (hosting)
