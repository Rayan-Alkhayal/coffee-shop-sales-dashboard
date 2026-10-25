# Coffee Shop Sales & Profitability Dashboard

An interactive Excel dashboard analyzing the sales and profit performance of a coffee shop across cities, products, payment methods, and hours of the day.

![Dashboard Preview](/images/dashboard.png.png)

*Dashboard labels are in Arabic*

## Project Overview
This project turns 1,000 coffee shop orders (2023) into an interactive dashboard with KPI cards, charts, and slicers. It answers 15 business questions about sales, costs, profit, products, locations, payment methods, and sales by time of day.

## Objective
Evaluate sales and profit performance and identify which cities, products, and customers drive revenue.

## Dataset
- 1,000 orders, 100 customers, 9 cities, 7 products (2023)
- Fields: order, customer, and product IDs; order date and time; payment method; location; product; quantity; unit cost; unit price; sales; total costs; profit
- Source: a training dataset provided by the instructor of a data analysis training program as a practice exercise. Because it is a training dataset, the insights below illustrate the analysis and should not be read as results of a real business.

## Tools & Techniques
- Microsoft Excel
- Excel Table with calculated columns: Sales = Quantity × Unit Price, Total Costs = Quantity × Unit Cost, Profit = Sales − Total Costs
- 14 PivotTables and 7 charts
- 6 KPI cards: total sales, total costs, total profit, total quantity, number of customers, profit margin
- Slicers for location and product
- Excel Data Model to count distinct customers

## Data Preparation
- Standardized the order date column, which mixed text and date values, into a single date format
- Calculated sales, costs, and profit per order, and checked that total sales minus total costs equals total profit
- Counted unique customers (100) instead of counting rows

## Key Insights
- Overall : SAR 18,922 in sales, SAR 8,940 in costs, and SAR 9,982 in profit (about 53% margin) from 2,529 units sold.
- Locations : Makkah (SAR 5,028) and Najran (SAR 4,689) generated about 51% of sales and led profit as well.
- Products : Americano with Milk was the top seller (SAR 4,976, about 26% of sales) and the most profitable (SAR 2,488), followed by Cappuccino in profit (SAR 2,295). Espresso was the lowest (SAR 282).
- Payment : Card payments made up about 89% of sales (SAR 16,763).
- Customers : Sales are spread widely; the top 5 customers account for about 9% of total sales.
- Time of day : Sales peak at 04:00 AM (SAR 1,153) and are lowest at 12:00 PM (SAR 487).

## How to Use
1. Download [coffee-shop-sales-dashboard.xlsx](coffee-shop-sales-dashboard.xlsx).
2. Open it in Microsoft Excel (desktop version recommended for slicers and refresh).
3. Open the Dashboard sheet and use the slicers (Location, Product) to filter the charts.

**Workbook contents : raw data, business questions, PivotTable analysis, and the dashboard (some sheet names are in Arabic).**
