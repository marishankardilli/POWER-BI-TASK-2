# Superstore Sales Analysis

## Overview

`mari visual.pbix` is a Power BI report for exploring Superstore sales performance. The report presents headline sales, profit, quantity, and discount metrics alongside regional, product, geographic, and time-based analysis.

## Report contents

The report contains one dashboard page: **Superstore Sales Analysis**.

| Area | Visual | What it shows |
|---|---|---|
| KPIs | Cards | Total Sales, Total Profit, Total Quantity, and Total Discount |
| Geography | Map | Total Sales by State/Province |
| Product mix | Donut chart | Total Quantity by Category |
| Regional mix | Donut chart | Total Quantity by Region |
| Product detail | Column chart | Total Sales by Sub-Category, sorted from highest to lowest |
| Profit trend | Line chart | Total Profit by order month |
| Year comparison | Bar chart | Total Profit by order year |
| Filtering | Slicers | Region and Sub-Category |

## Data model

The visuals use the `samplesuperstore` table. Fields referenced by the report include:

- `Order Date`
- `State/Province`
- `Region`
- `Category`
- `Sub-Category`
- `Total Sales`
- `Total Profit`
- `Total Quantity`
- `Total Discount`

The page is configured for drillthrough on **Order Date**, so it can receive an Order Date context from another report page or visual when used in a larger report experience.

## How to use the dashboard

1. Open `mari visual.pbix` in Power BI Desktop.
2. Use the **Region** and **Sub-Category** slicers to narrow the analysis.
3. Select a segment, bar, or map location to cross-filter the other visuals.
4. Hover over a data point for its detailed value.
5. Clear selections or slicer values to return to the full report view.

## Notes

- The dashboard has a single page and uses a 960 × 720 canvas.
- Its report setting permits export of summarized data.
- This README documents the report definition embedded in the PBIX file. It does not include source-system connection details, refresh schedules, or measure formulas because those details are not exposed in the report-definition metadata inspected here.

## Requirements

- Power BI Desktop (current version recommended) to open and edit the `.pbix` file.



<img width="682" height="507" alt="Screenshot 2026-09-07 225501" src="https://github.com/user-attachments/assets/e9293461-84ec-45fd-b10c-5466fbb75da9" />


