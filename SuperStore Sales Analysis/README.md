# Superstore Sales Performance Dashboard

### Business Intelligence & Interactive Dashboard Development
**AnalystLab Africa — Data Analytics Internship Programme, Week 2**

![Status](https://img.shields.io/badge/status-complete-2E74B1) ![Tool](https://img.shields.io/badge/tool-Power%20BI-F2C811) ![Dataset](https://img.shields.io/badge/dataset-Superstore%20Sales-1F3864)

---

## Overview

A national retail company needed a way for senior management to actually *see* the business — sales performance, profitability, customer behavior, and regional results — without waiting on manual reports. This project puts me in the role of a Junior Business Intelligence Analyst at AnalystLab Africa Consulting, tasked with turning raw retail transaction data into a fully interactive executive dashboard in Power BI.

The result is a 3-page dashboard covering **$2.30M in total sales**, **$286.4K in total profit**, and **5,009 orders** across four regions and three customer segments, from 2014–2017.

## Business Questions

1. What is the overall sales performance of the company?
2. Which regions generate the highest sales and profit?
3. Which customer segments contribute the most revenue?
4. Which product categories perform best?
5. Which products are the most profitable?
6. What trends can be observed over time?
7. What recommendations should management implement to improve business performance?

## Dashboard Structure

**Cover Page** — Executive landing page with headline KPIs and navigation to each section.

**Sales Performance** — Total Sales, Average Sales, Total Orders, Top 5 Products, Sales by State (map), Sales by Segment/Category/Region, and a 12-month Sales Trend.

**Profitability Analysis** — Profit Margin %, Total Profit, Top 5 Products by profit, Profit by State (map), Profit by Segment/Category/Region, a 12-month Profit Trend, and Region/Category/Year filters.

**Insights & Recommendations** — Key Insights, Business Risks, Business Opportunities, and actionable Recommendations, all directly evidenced by the dashboard.

Every visual is fully cross-filterable — selecting a state in the Matrix, a slice in a donut chart, or a bar in any chart dynamically filters the rest of the page, so management can drill into any region, segment, or category interactively.

## Key Insights

1. **The West Region leads in both sales and profit** — $0.73M in sales and $0.11M in profit, ahead of every other region.
2. **Technology is the most profitable category** ($0.15M profit), while **Furniture lags behind** at just $0.02M.
3. **The Consumer segment generates the highest revenue**, contributing over 50% of total sales.
4. **Sales rise strongly in the last quarter of the year**, with November and December consistently the two strongest months.
5. **Profit is concentrated in a small number of top-performing products** — the top 5 products alone account for a disproportionate share of total profit.

## Business Risks

- Heavy dependence on the West Region for both sales and profit.
- Weak profitability in the Furniture category.
- Over-reliance on a small number of high-profit products.

## Business Opportunities

- Replicate West Region success in the Central and South regions.
- Improve or reduce underperforming Furniture items.
- Push high-margin Technology products harder.

## Recommendations

1. Strengthen sales and marketing efforts in the Central and South regions, using approaches that worked in the West.
2. Review the Furniture category — identify loss-making products and consider reducing discounts, renegotiating costs, or discontinuing the worst performers.
3. Increase focus on Technology products with more marketing budget and sales attention.
4. Protect and promote the top profitable products, ensuring strong stock availability and visibility.
5. Align inventory and marketing activity with seasonal sales peaks, especially Q4.
6. Apply stricter control on discount levels, particularly for low-margin categories.

## Repository Contents

| File | Description |
|---|---|
| `Business_Intelligence_Interactive_Dashboard.pbix` | Full Power BI project file — data model, Power Query transformations, and all report pages |
| `Business_Intelligence_Dashboard.pdf` | Static export of all dashboard pages |
| `Business_Intelligence_Overview_Report.docx` | Part 1–2: what BI is, why dashboards matter, business objective, and full data preparation documentation |
| `Executive_Summary_Report.pdf` | One-page summary of KPIs, key findings, risks, and recommendations for a management audience |


## Data Preparation

Using Power Query in Power BI: imported the dataset (9,994 rows, 21 columns), confirmed zero missing values and zero duplicate rows, verified/corrected data types across all columns, removed the unused Row ID column, and added helper columns (Year, Month, Month Name, Profit Margin) to support the dashboard's visuals. Full detail is in the Business Intelligence Overview Report above.

## Dataset

**Superstore Sales Dataset** — 9,994 retail transactions across the United States, 2014–2017, covering orders, customers, products, regions, sales, and profit.
Source: [Kaggle — vivek468/superstore-dataset-final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Tools Used

- **Microsoft Power BI** — data modeling, Power Query transformations, and interactive dashboard design
- **Microsoft Word (exported to PDF)** — Business Intelligence Overview Report and Executive Summary Report

## Author

**Adesola Sobambo**
Data Analytics Intern, AnalystLab Africa
