# Superstore Sales Analysis

## Problem Statement
A global superstore needs to identify profitable product categories and high-performing regions to optimize inventory, pricing, and marketing strategies.

## Business Impact
This analysis helps the business focus resources on high-margin categories (especially Technology) and strong regions (West), potentially improving overall profitability.

## Dataset
- **Source**: Sample Superstore Dataset (Public)
- **Rows**: 9,994 orders
- **Time Period**: 2014 - 2017

## Key Insights
- **Technology** is the best performing category: **$581,819 profit** with **15.61% margin**
- **Furniture** has high sales but very low profitability (**3.88% margin**)
- **West** region significantly outperforms other regions in both sales and profit

## Tools & Skills Used
- PostgreSQL + pgAdmin4
- SQL (Aggregation, Grouping, Date functions)
- Tableau Public for visualization
- Data loading and cleaning

## Visualizations

![Total Profit by Product Category](profit_by_category.png)

## How to Reproduce
1. Create database and table using `queries.sql`
2. Import the CSV data
3. Run analysis queries

## Future Improvements
- Add customer segmentation analysis
- Year-over-year growth calculations
- Dashboard in Tableau

---

**Project completed as part of Data Analyst Portfolio**