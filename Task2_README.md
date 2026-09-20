# Sales Performance Analysis — Alfido Tech

**Task 2 of 3 — Alfido Tech Data Analytics Internship Program**

## Overview
Analysis of 9,800 sales line items across 4,922 orders from 793 customers (Jan 2015 – Dec 2018), covering $2.26M in total sales, to understand revenue trends, top-performing categories/products/regions, seasonality, and shipping performance, with actionable recommendations for Alfido Tech.

**Dataset:** Superstore Sales Dataset (Kaggle) — `superstore_final_dataset.csv`

## Files in this repo
| File | Description |
|---|---|
| `Sales_Performance_Analysis.ipynb` | Full Jupyter notebook — data cleaning, feature engineering, trend/seasonality analysis, category/product/regional/segment breakdowns, shipping analysis (executed, all outputs included) |
| `Sales_Performance_Analysis_Report.pdf` | Detailed 10-page analytical report — methodology, findings, and recommendations |
| `Task2_Submission_Summary.pdf` | 1-page submission summary — executive summary, key findings, top recommendations, key charts, and notebook screenshots |

## Approach
1. **Data cleaning** — confirmed date format (DD/MM/YYYY), checked for duplicates/missing values/invalid data, verified date consistency.
2. **Feature engineering** — extracted year, month, quarter, weekday, and shipping delay (days) from order/ship dates.
3. **Trend analysis** — yearly and monthly sales trends, year-over-year growth, seasonality patterns.
4. **Category/product/regional analysis** — performance breakdowns by category, sub-category, product, region, and state.
5. **Customer analysis** — segment performance and revenue concentration (Pareto-style analysis).
6. **Shipping analysis** — order volume and delivery speed by shipping mode.

## Key Findings
- Sales grew overall across the period — a 2016 dip (−4.3%) was followed by strong growth in 2017 (+30.6%) and 2018 (+20.3%).
- Strong, predictable seasonality — September, November, and December are peak months, each 2–3x a typical mid-year month.
- **Technology** drives the most revenue per order (36.6% of revenue from the fewest orders); **Office Supplies** drives the most order volume (60% of line items) at the lowest average value.
- Revenue is broadly spread across customers — it takes ~50% of customers to reach 80% of revenue, healthier than typical 80/20 concentration.
- **Standard Class** shipping dominates (59.8% of orders) despite being the slowest option (~5 day average delay).

## Top 5 Recommendations
1. Plan inventory and staffing around the September/November/December seasonal peak.
2. Promote faster shipping tiers more assertively at checkout.
3. Double down on Technology as a margin/value driver via bundling and upsell.
4. Use Office Supplies as a traffic driver, then cross-sell higher-value categories.
5. Investigate and target underperforming states for incremental revenue.

---
*Prepared as part of the Alfido Tech Data Analytics Internship Program.*
