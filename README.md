# Coffee Shop Sales Performance Analysis

Excel-based sales analytics project transforming 149,000+ raw transaction records into an interactive business dashboard. The workflow covers data cleaning, feature engineering, and pivot-based analysis to surface revenue trends, product performance, and store-level insights for a multi-location coffee shop chain in New York, NY (Lower Manhattan, Hell's Kitchen, Astoria).

## Key Results

- **Total Revenue:** $10,022,902 across 214,470 units sold
- **149,000+ transaction records** cleaned and structured from raw POS data
- **~107% revenue growth** from January to June 2023
- **Tea** was the highest-revenue product category ($260,388 in June alone)
- Sales patterns analyzed by time period (Morning/Afternoon/Evening), store location, product category, product segment, and product detail

## Project Structure

| Sheet | Description |
|---|---|
| **InputData** | Cleaned transaction-level dataset (149K+ rows, 18 columns) with 5 engineered columns (Product, Total Revenue, Day, Month, Year) added on top of the original raw fields to support aggregation and pivoting |
| **Analysis** | PivotTables breaking down revenue by month, product, category, segment, time period, and store location, including month-over-month growth calculations |
| **Dashboard** | Interactive dashboard with slicers for dynamic filtering across dimensions |

> Note: The original raw data sheet was removed from this workbook to keep file size under GitHub's upload limit. InputData retains the full cleaned dataset used for analysis.

## Workflow

1. **Data Cleaning** : Raw transaction data validated and structured
2. **Feature Engineering** : Derived fields added (Total Revenue, Day, Month, Year, Product) to enable time-based and product-based aggregation
3. **Analysis** : PivotTables built on InputData to calculate revenue by category, product, time period, and location, plus month-over-month growth rate
4. **Visualization** : Dashboard sheet consolidates key metrics and PivotCharts with interactive slicers for exploration

## Tools

Microsoft Excel (PivotTables, PivotCharts, Slicers, formulas for feature engineering)

## Skills Demonstrated

Data cleaning · Feature engineering · Exploratory data analysis · KPI reporting · Dashboard design · Business insight generation
