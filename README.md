# Excel Sales Dashboard

An interactive Excel dashboard that analyses 2026 sales performance for an outdoor, travel and fitness equipment retailer operating across Europe. It brings together revenue, profitability and product trends in a single view, so stakeholders can explore the numbers without writing any formulas.

## Overview

The workbook is built on 2,707 order records covering 17 countries and 20 products across five categories: Camping, Hiking, Travel, Cycling and Fitness. Orders are grouped by region, sales channel and customer type, which allows performance to be compared from several angles.

**Headline figures (2026)**

| Metric | Value |
|---|---|
| Total revenue | ~€645K |
| Gross profit | ~€296K |
| Gross margin | ~45.9% |
| Units sold | 6,698 |
| Orders | 2,707 |

## Key Insights

- **Revenue by category:** Camping and Hiking generate the most revenue, while Fitness and Cycling carry the highest gross margins (roughly 51% and 49%).
- **Sales channels:** The Online Store is the largest channel, contributing around 40% of total revenue. Corporate sales are the second largest but have the lowest margin of the four channels.
- **Regions:** Western and Central Europe together account for just over 60% of revenue.
- **Seasonality:** Revenue builds through the first half of the year, peaks in June, and shows a secondary rise in November.
- **Top products:** Summit Backpack 45L, Alpine Tent 4P and Trail Tent 2P lead on revenue.

## Workbook Structure

| Sheet | Purpose |
|---|---|
| **Data** | Cleaned transactional dataset: order date, geography, channel, customer type, product, pricing, discount, cost, revenue, COGS and gross profit |
| **Pivot Tables** | Pivot tables that summarise revenue, profit and volume by month, country, channel and region |
| **Dashboard** | Charts, KPI cards and slicers for interactive filtering |

## Features

- KPI summary covering revenue, gross profit, margin, units sold and order count
- Monthly revenue and profit trends
- Breakdowns by country, region, sales channel and customer type
- Slicer-based filtering for quick, interactive exploration
- Calculated fields for COGS, gross profit and gross margin %

## How to Use

1. Download `Excel_Sales_Dashboard.xlsx`.
2. Open it in Microsoft Excel (2016 or later is recommended, as slicers and pivot charts are used).
3. Go to the **Dashboard** sheet and use the slicers to filter the data.
4. If you edit the **Data** sheet, use *Data → Refresh All* to update the pivot tables and charts.

## Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers, calculated fields)

## Notes

The dataset is used for demonstration and portfolio purposes.
