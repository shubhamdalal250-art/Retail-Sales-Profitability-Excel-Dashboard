# Retail Sales & Profitability Analysis — Advanced Excel Dashboard

## Project Overview

Developed an interactive retail sales and profitability reporting dashboard using **Microsoft Excel 365**, analyzing 9,994 transaction line items from the Sample Superstore dataset (2014–2017).

The project demonstrates how Excel can be used to transform raw sales data into refreshable business reports, interactive KPI monitoring, and actionable profitability insights.

## Business Objectives

- Analyze revenue, profit, and profit margin across retail operations.
- Identify high-performing and loss-making product categories.
- Monitor monthly revenue trends.
- Compare regional and customer segment performance.
- Evaluate top-selling products and average order value.
- Enable interactive business reporting using slicers.

## Tools and Techniques

**Microsoft Excel 365**

- Power Query for data cleaning, type conversion, and transformation
- Advanced formulas: SUMIFS, COUNTIFS, XLOOKUP, INDEX-MATCH, IF, IFERROR
- FILTER and UNIQUE for distinct-order analysis
- PivotTables and PivotCharts
- Slicers and Report Connections
- GETPIVOTDATA for dynamic KPI reporting
- Conditional formatting
- Date-based revenue analysis and month-over-month growth

## Dashboard KPIs

| KPI | Overall Result |
|---|---:|
| Total Revenue | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Profit Margin | 12.47% |
| Average Order Value | $458.61 |

**AOV definition:** Total revenue divided by the number of distinct orders. Under category or segment filtering, the metric reflects the selected subset of order lines and the distinct orders represented by that subset.

## Key Business Findings

1. **Technology leads category profitability**, generating $145,454.95 in profit with a 17.40% margin.

2. **Furniture has relatively weak profitability**, with a 2.49% profit margin. Tables recorded a net loss of $17,725.48, indicating a need to investigate pricing, discounts, and product mix.

3. **Customer segments show different margin patterns.** Consumer generated the highest revenue, approximately $1.16 million, while Home Office achieved the highest profit margin at 14.03%.

## Dashboard Features

- Four interactive management KPIs
- Four slicers: Region, Category, Segment, Order Year
- Monthly revenue trend chart
- Regional profit comparison
- Category profitability chart
- Top 10 products by revenue
- Supporting formula-based analysis and business findings

## Dashboard Preview

![Retail Sales Dashboard](screenshots/dashboard_overview.png)

## Dataset

**Source:** Sample Superstore dataset

https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The dataset represents a fictional U.S. retail business and contains sales, profit, customer, product, and geographic information. Monetary figures are reported in the source dataset's USD context.

## How to Use

1. Download `dashboard/Retail_Sales_Dashboard.xlsx`.
2. Open it using Microsoft Excel 365 desktop.
3. Navigate to the `Dashboard` worksheet.
4. Use the four slicers to filter the KPIs and visualizations.
5. Explore the `Formula_Lab`, `Pivot_analysis`, and `Business_Insights` worksheets for supporting calculations and findings.

**Refresh note:** The Power Query source connection references the original CSV path used during development. To refresh on another computer, download the dataset and update the Power Query source location through Data Source Settings or the query's Source step.

## Project Scope

This project focuses exclusively on Microsoft Excel, demonstrating advanced spreadsheet analytics, interactive reporting, data quality validation, and business interpretation without using Python, SQL, or Power BI for implementation.

## Author

Shubham

