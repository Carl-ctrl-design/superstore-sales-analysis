# Superstore Retail Sales Performance Analysis

![Excel](https://img.shields.io/badge/Microsoft%20Excel-Advanced-217346)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Dataset](https://img.shields.io/badge/Dataset-9%2C994%20rows-blue)
![Coverage](https://img.shields.io/badge/Coverage-2014--2017-orange)

> A structured profitability audit of a multi-region retail business. The top-line numbers looked healthy. The analysis revealed where the money was quietly disappearing.

---

## Business problem

A retail chain needed to understand what was actually driving margin performance across regions, product categories, and customer segments. Revenue looked strong on the surface. The real question was why profit was not keeping pace with sales volume.

---

## What I built

A fully structured Excel analytics workbook covering data cleaning and transformation in Power Query, PivotTable analysis across five business dimensions, a KPI dashboard with headline metrics, and data-backed recommendations for each finding.

**Five areas of analysis:**

1. Product performance: revenue and profit by category and sub-category
2. Regional analysis: profitability comparison across all four regions
3. Discount impact: correlation between discount bands and profit margins
4. Customer segmentation: value and profitability by segment type
5. Trend analysis: year-on-year sales performance from 2014 to 2017

---

## Key findings

**1. Two product lines are quietly destroying margin.**
Tables and Bookcases generate significant revenue but produce negative profit margins. High sales volume masked the problem. These are structural pricing or cost issues, not volume problems, which makes them more dangerous.

**2. Discounting above 20% is a loss-making policy.**
Profit margin collapses from +29.5% on zero-discount orders to -119% on heavily discounted ones. 1,458 orders across the dataset are loss-making purely because of excessive discounting. This is a pricing governance failure, not a market problem.

**3. The Central region is underperforming on margin, not revenue.**
Central sits third in total revenue but last in profit margin at 7.9%. That gap between revenue rank and margin rank points directly to aggressive discounting or inefficient pricing in that region specifically.

**4. Technology carries the business.**
Highest revenue and highest profitability of any category. It is the core growth driver and the margin anchor. The business should be investing in expanding Technology, not defending Furniture.

**5. Corporate segment is more valuable than it appears.**
Corporate delivers higher margin per order than the Consumer segment. If the business is treating both segments with the same pricing and discount approach, it is leaving money on the table with its most profitable customers.

---

## Recommendations

| Finding | Recommended action |
|---|---|
| Tables and Bookcases losing money | Reprice or discontinue. Run a cost audit before the next buying cycle |
| Discounts above 20% cause losses | Cap discount authority at 20%. Any exception requires approval |
| Central region margin lagging | Audit Central pricing. Identify which reps or categories are driving discounts |
| Technology drives profit | Expand SKU depth in Technology. Prioritise in marketing spend |
| Corporate segment underserved | Create a dedicated Corporate pricing tier with margin floors |

---

## Dashboard

![Dashboard Preview](dashboard_screenshot.png)

The Excel dashboard delivers five headline KPIs at the top: Total Revenue, Total Profit, Profit Margin, Number of Orders, and Loss-Making Orders. Supporting visuals break down performance by category, region, discount band, and customer segment with conditional formatting to surface problems instantly.

---

## Files

| File | Description |
|---|---|
| `Superstore_Sales_Analysis_CarlWaiti.xlsx` | Full Excel workbook including Power Query pipeline, PivotTables, and KPI dashboard |
| `dashboard_screenshot.png` | Dashboard preview |

---

## Dataset

**Source:** Kaggle Superstore Sales Dataset
**Rows:** 9,994 orders
**Period:** 2014 to 2017
**Fields:** Order details, product categories, customer segments, regional data, revenue, discount, and profit

---

## Portfolio context

| # | Project | Tools | Link |
|---|---|---|---|
| 1 | Superstore Sales Analysis | Excel, PivotTables, KPI Dashboard | This repo |
| 2 | Olist E-Commerce SQL Analysis | PostgreSQL 17, CTEs, Window Functions | [View](https://github.com/Carl-ctrl-design/olist-sql-analysis-project) |
| 3 | Olist Power BI Dashboard | Power BI, DAX, PostgreSQL Live Connection | [View](https://github.com/Carl-ctrl-design/olist-powerbi-dashboard) |
| 4a | Safaricom SQL Financial Analysis | PostgreSQL 17, Primary Source Data | [View](https://github.com/Carl-ctrl-design/safaricom_sql_financial_analysis) |
| 4b | Safaricom Power BI Dashboard | Power BI, DAX, PostgreSQL | [View](https://github.com/Carl-ctrl-design/safaricom-powerbi-dashboard) |

---

## Full case study

[View on Portfolio](https://carl-ctrl-design.github.io/C.Waiti/projects/retail-sales.html)

---

## Author

**Carlton Waiti**, Data and Business Analyst, Nairobi, Kenya

BSc Economics and Finance, Kenyatta University (2026)
Google Data Analytics Professional Certificate

[GitHub](https://github.com/Carl-ctrl-design) · [Portfolio](https://carl-ctrl-design.github.io/C.Waiti) · [LinkedIn](https://www.linkedin.com/in/carlton-waiti)
