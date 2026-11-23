# Retail Sales Analysis Dashboard

An end-to-end retail data analysis project using **Microsoft Excel** and **Power BI** to uncover sales trends, regional profitability, and category performance across 2024.

## Dashboard Preview
![Retail Sales Analysis Dashboard](Retail%20Sales%20Analysis%20Dashboard%20Screenshot.png)

## Project Overview
The goal of this project is to transform raw retail transaction data into actionable business insights. After cleaning and standardizing the raw dataset in Excel, an interactive Power BI report was built to monitor key performance indicators (KPIs), regional profit margins, and monthly revenue trends.

## Key Metrics & Insights
* **Overall Performance:** Generated **₹28.56M** (displayed as **29M**) in total sales and **₹3.52M** in total profit, achieving an overall profit margin of **12.33%**.
* **Regional Performance:** **North** led both revenue (**₹9.24M**) and total profit (**₹1.25M**), while **West** achieved the highest profit margin (**16.38%**). **East** recorded the lowest profit margin (**9.05%**), highlighting an opportunity for cost optimization.
* **Category Breakdown:** **Furniture** was the top-performing category (**₹10.40M** sales, **₹1.27M** profit), followed by **Office Supplies** (**₹9.56M** sales, **₹0.99M** profit) and **Technology** (**₹8.60M** sales, **₹1.26M** profit).
* **Seasonal Trends:** **September** recorded the highest monthly sales (**₹3.34M**), followed by **March** (**₹2.98M**), whereas **April** saw the sharpest dip (**₹1.12M**).

## Data Cleaning & Methodology
* **Data Standardization (Excel):** Removed duplicate order records (250 raw rows to 240 unique transactions), standardized mixed `Order Date` formats, normalized `Region` text casing (17 rows fixed), and handled missing `Postal Code` entries (12 rows labeled as `Unknown`).
* **Data Modeling & DAX (Power BI):** Created custom DAX measures for `Total Sales`, `Total Profit`, `Profit Margin %`, and chronological `Month Number` sorting.

## Tools & Skills Used
* **Microsoft Excel:** Data cleaning, formula-based validation, pivot summaries, and KPI documentation (`Retail Sales Analysis Project final.xlsx`).
* **Microsoft Power BI:** Data modeling, DAX calculations, interactive slicers, and dashboard design (`Retail Sales Analysis Dashboard Project .pbix`).

## Repository Contents
* `Retail Sales Analysis Dashboard Project .pbix` — Interactive Power BI report file.
* `Retail Sales Analysis Project final.xlsx` — Raw data, cleaned dataset, summary tables, and formula documentation.
* `Retail Sales Analysis Dashboard Screenshot.png` — High-resolution preview of the final dashboard.

## How to Use
1. Download `Retail Sales Analysis Dashboard Project .pbix`.
2. Open the file using **Power BI Desktop** (free from Microsoft).
3. Use the **Region** and **Category** slicers on the right panel to filter the KPIs and charts dynamically.
