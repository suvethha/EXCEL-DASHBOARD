# BlinKit Sales Dashboard
---------
## Overview

The Blinkit Grocery Dashboard is a dynamic Excel‑based analytics solution designed to help businesses understand and optimize their quick‑commerce performance. It consolidates operational and sales data into an interactive interface, enabling teams to monitor real‑time order trends, customer behavior, and profitability metrics. Built for fast‑moving grocery delivery environments, the dashboard empowers decision‑makers with clear, actionable insights.

The dashboard highlights essential KPIs such as Total Sales,Average Sales,No of Items,Average Rating. With interactive slicers and filters, users can explore data across product categories, delivery partners, and time periods, making the dashboard adaptable to multiple business scenarios.

## Sample Dataset 

### Orders Table

| Item Fat Content | Serial No | Item Identifier | Item Type             | Outlet Establishment Year | Outlet Identifier | Outlet Location Type | Outlet Size | Outlet Type       | Item Visibility | Item Weight | Sales    | Rating |
|------------------|-----------|-----------------|-----------------------|---------------------------|-------------------|----------------------|-------------|-------------------|-----------------|-------------|----------|--------|
| Regular          | 1         | FDX32           | Fruits and Vegetables | 2012                      | OUT049            | Tier 1               | Medium      | Supermarket Type1 | 0.1000135       | 15.1        | 145.4786 | 5      |
| Low Fat          | 2         | NCB42           | Health and Hygiene    | 2022                      | OUT018            | Tier 3               | Medium      | Supermarket Type2 | 0.008596051     | 11.8        | 115.3492 | 5      |
| Regular          | 3         | FDR28           | Frozen Foods          | 2016                      | OUT046            | Tier 1               | Small       | Supermarket Type1 | 0.025896485     | 13.85       | 165.021  | 5      |
| Regular          | 4         | FDL50           | Canned                | 2014                      | OUT013            | Tier 3               | High        | Supermarket Type1 | 0.042277867     | 12.15       | 126.5046 | 5      |
| Low Fat          | 5         | DRI25           | Soft Drinks           | 2015                      | OUT045            | Tier 2               | Small       | Supermarket Type1 | 0.033970195     | 19.6        | 55.1614  | 5      |
| low fat          | 6         | FDS52           | Frozen Foods          | 2020                      | OUT017            | Tier 2               | Small       | Supermarket Type1 | 0.005505481     | 8.89        | 102.4016 | 5      |
| Low Fat          | 7         | NCU05           | Health and Hygiene    | 2011                      | OUT010            | Tier 3               | Small       | Grocery Store     | 0.098312421     | 11.8        | 81.4618  | 5      |


## KPI Table

The following primary KPIs:

| KPI Name          |  Formula                        |
|-------------------|---------------------------------|
| Total Sales       | SUM(Sales)                      |
| Avg Sales         | AVERAGE(Sales)                  |
| No of Items       | COUNT(Items)                    |
| Avg Rating        | AVERAGE(Rating)                 |
     
---

## Problem Statements Solved

The Blinkit Grocery Dashboard answers several business questions by uncovering patterns in sales performance and revenue contribution.
The dashboard also reveals customer behavior through rating trends and item‑level performance insights.

1. **Primary KPIs** – Total Sales, Average Sales, Number of Items Sold, Average Rating


