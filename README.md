# 🛒 Blinkit Sales Analysis Dashboard
 
An interactive Power BI dashboard analyzing Blinkit (India's last minute app) grocery sales across outlet types, locations, item categories, and fat content segments.
 
![image alt](https://github.com/vaishnavi-selvamraj/blinkit-sales-analysis/blob/main/Screenshot%20(66).png?raw=true)
 
---
 
## 🔍 Overview
 
This dashboard provides a comprehensive view of Blinkit's grocery retail performance. It helps operations and category teams understand which outlet types, sizes, and locations drive the most revenue — and how item type and fat content influence buying patterns. Dynamic filters allow slicing by outlet location type, outlet size, and item type.
 
---
 
## 📈 Key Metrics
 
| Metric | Value |
|---|---|
| Total Sales | $1.20M |
| Average Sales | $141 |
| No. of Items | 8,523 |
| Average Rating | 3.9 |
 
---
 
## 🧩 Dashboard Features
 
### Slicers / Filters
- **Outlet Location Type** — All / Tier 1 / Tier 2 / Tier 3
- **Outlet Size** — All / Small / Medium / High
- **Item Type** — All / specific item categories
### Metric Toggle
Switch the main charts between: **Total Sales · Avg Sales · No of Items · Avg Rating**
 
### Visuals Included
 
| Visual | Description |
|---|---|
| KPI Cards | Total sales, avg sales, no. of items, avg rating |
| Fat Content (Donut) | Low Fat ($425.36K) vs Regular ($776.32K) split |
| Fat by Outlet (Bar) | Low Fat vs Regular revenue per outlet tier |
| Item Type (Bar) | Revenue across 16 item categories |
| Outlet Establishment (Line) | Sales trend from 2012 to 2022 |
| Outlet Size (Donut) | Medium / Small / High size revenue split |
| Outlet Location (Bar) | Tier 1 / Tier 2 / Tier 3 revenue comparison |
| Outlet Type (Table) | Detailed breakdown by outlet type — sales, avg sales, items, rating, visibility |
 
---
 
## 🍎 Top Item Types by Revenue
 
| Rank | Item Type | Revenue |
|---|---|---|
| 1 | Fruits & Vegetables | $0.18M |
| 2 | Snack Foods | $0.18M |
| 3 | Household | $0.14M |
| 4 | Frozen Foods | $0.12M |
| 5 | Dairy | $0.10M |
| 6 | Canned | $0.09M |
| 7 | Baking Goods | $0.08M |
| 8 | Health & Hygiene | $0.07M |
 
---
 
## 🏪 Outlet Type Breakdown
 
| Outlet Type | Total Sales | Avg Sales | No. of Items | Avg Rating |
|---|---|---|---|---|
| Supermarket Type2 | $131.48K | $142 | 928 | 4 |
| Supermarket Type1 | $787.55K | $141 | 5,577 | 4 |
| Grocery Store | $151.94K | $140 | 1,083 | 4 |
| Supermarket Type3 | $130.71K | $140 | 935 | 4 |
 
> **Supermarket Type1 dominates** with ~66% of total sales and the highest item count.
 
---
 
## 📍 Outlet Location (Tier) Breakdown
 
| Tier | Revenue |
|---|---|
| Tier 3 | $472.13K (highest) |
| Tier 2 | $393.15K |
| Tier 1 | $336.40K |
 
---
 
## 📐 Outlet Size Breakdown
 
| Size | Revenue |
|---|---|
| Medium | $507.9K |
| Small | $444.79K |
| High | $248.99K |
 
---
 
## 📅 Outlet Establishment Trend
 
Sales peaked around **2018 (~$205K)** and have stabilized in the **$129K–$133K range** from 2020 to 2022, suggesting market maturation.
 
---
 
## 🚨 Key Insights
 
- **Regular fat items** outsell Low Fat items nearly 2:1 ($776K vs $425K)
- **Fruits & Vegetables and Snack Foods** are the top two revenue categories
- **Supermarket Type1** accounts for ~66% of all sales
- **Tier 3 outlets** generate the most revenue despite being lower-tier locations — indicating strong suburban/rural demand
- **Medium-sized outlets** lead by revenue among outlet size segments
- All outlet types maintain a consistent **average rating of 4**, indicating uniform customer satisfaction
---
 
## 🛠️ Tech Stack
 
- **Tool:** Microsoft Power BI Desktop
- **Data:** BlinkIT Grocery Dataset (CSV/Excel)
- **Data tables:** BlinkIT Grocery Data, Metrics
- **DAX Measures:** Total Sales, Avg Sales, No. of Items, Avg Rating, Avg Item Visibility



