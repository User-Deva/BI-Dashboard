# Demand Forecasting Dashboard

An interactive BI dashboard built with Tableau Public, analyzing 76,000 rows of demand forecasting data across stores, regions, product categories, and seasons.

## Live Dashboard
[View on GitHub Pages](https://YOUR_USERNAME.github.io/demand-forecasting-dashboard)

[View on Tableau Public](https://public.tableau.com/views/DemandForecasting_17761788157530/DemandForecasting)

## Dataset Overview
| Field | Details |
|---|---|
| Rows | 76,000 |
| Columns | 16 |
| Date Range | 2022 – 2023 |
| Categories | Electronics, Clothing, Groceries |
| Regions | North, South, East, West |

## Columns in the dataset
- `Date` — Transaction date
- `Store ID` / `Product ID` — Identifiers
- `Category` / `Region` — Dimensions for grouping
- `Inventory Level` — Stock on hand
- `Units Sold` / `Units Ordered` — Sales & order volume
- `Price` / `Discount` / `Competitor Pricing` — Pricing data
- `Weather Condition` / `Seasonality` — Environmental factors
- `Promotion` / `Epidemic` — Event flags (0 = No, 1 = Yes)
- `Demand` — Target variable

## Dashboard Charts
1. **Demand Trend** — Monthly demand over time by category (line chart)
2. **Demand by Region** — Regional breakdown (stacked bar chart)
3. **Seasonality Impact** — Demand across seasons (box plot)
4. **Promotion Effect** — Avg demand with vs without promotion (bar chart)
5. **Inventory vs Sales** — Stockout risk analysis (scatter plot)

## How to run locally
Just open `index.html` in any browser — no server needed.

## Tech Stack
- Tableau Public (dashboard)
- HTML/CSS (wrapper page)
- GitHub Pages (hosting)
