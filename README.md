# Blinkit Grocery Sales Dashboard

An interactive Power BI dashboard analysing 8,523 rows of Blinkit grocery sales data — covering data cleaning, outlet performance, and product visibility trends.

**Tech stack:** Power BI · DAX · Power Query (M) · Excel

![Dashboard Overview](screenshots/overview.png)

## Overview

This project explores sales performance across Blinkit's outlet network, with a focus on resolving data quality issues in the raw dataset and surfacing insights that challenge conventional retail assumptions.

## Data Cleaning

- Used Power Query (M) to resolve outlet size contradictions across 2,410 rows (28% of the dataset) affecting 3 outlet IDs, where the same outlet had conflicting size labels across records
- Standardized categorical fields and handled missing values prior to modeling

## Key Insights

- **Item visibility vs. sales:** A scatter plot analysis revealed a near-zero correlation between shelf visibility and sales — a counterintuitive finding that challenges standard retail shelf-placement strategy
- **Outlet tier performance:** Tier 3 outlets emerged as the top revenue contributors despite having lower customer footfall than Tier 1/2 outlets, suggesting stronger per-visit basket sizes or loyalty effects worth investigating further

## Dashboard Pages

1. **Overview** — sales KPIs, revenue by outlet type, category breakdown
2. **Deep Dive** — item visibility vs. sales scatter plot, outlet tier performance, size-adjusted revenue comparison

![Deep Dive Page](screenshots/deep_dive.png)

## Files

- `Blinkit_Sales_Dashboard.pbix` — full Power BI file (open in Power BI Desktop to explore interactively)
- `screenshots/` — static dashboard views for quick reference
- `data/` — source dataset (if included)

## How to Use

1. Download `Blinkit_Sales_Dashboard.pbix`
2. Open in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free)
3. Explore filters and drill-throughs interactively
