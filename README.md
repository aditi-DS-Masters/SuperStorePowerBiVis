# SuperStorePowerBiVis

## Overview
Interactive Power BI dashboard that analyzes Superstore sales performance by Region and Category.

## Contents
- `SuperstoreStore.pbix` - Power BI report (open with Power BI Desktop)
- `SuperStore.pdf` - dashboard preview images
- [Superstore Sales Dashboard (PDF)](./SuperStore.pdf)

## Key features
- KPIs: Total Sales, Total Profit, Profit Margin
- Sales by Category & Sub-Category
- Sales trend (monthly) with YoY comparisons
- Geographic sales (State / Region)
- Interactive slicers for Year, Region, Category


## DAX highlights
- `Total Sales = SUM(Orders[Sales])`
- `Profit Margin = DIVIDE([Total Profit], [Total Sales])`
- `Sales LY = CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Date'[Date]))`

Dataset source: [Kaggle Superstore](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
