# 📊 Power BI Sales Performance Dashboard

## 📌 Project Overview

This project focuses on analyzing sales data and developing an interactive Sales Performance Dashboard using Microsoft Power BI. The dashboard provides meaningful business insights into sales revenue, profit, product performance, sales categories, payment methods, and monthly sales trends.

The project uses Excel datasets containing sales transaction details and product master information. Data cleaning and transformation are performed using Power Query, while DAX is used to create calculated columns and measures for business analysis.

## 🎯 Project Objectives

- Analyze overall sales and profit performance.
- Identify top-performing products and categories.
- Monitor monthly and yearly sales trends.
- Analyze sales performance by sales type and payment mode.
- Evaluate discounts and their impact on profitability.
- Create interactive visualizations for business decision-making.

## 🛠️ Tools & Technologies

- Microsoft Power BI – Dashboard development and data visualization.
- Power Query – Data cleaning and transformation.
- DAX – Calculated columns and measures.
- Microsoft Excel– Data source and dataset management.


## 🔄 Data Cleaning & Transformation

Data preparation was performed using Power Query.

- Checked and corrected column data types.
- Checked missing and blank values.
- Removed unnecessary spaces using Trim and Clean.
- Verified product IDs across both tables.
- Prepared data for modeling and visualization.

## 🔗 Data Modeling

Created a One-to-Many relationship between:
- Master Data (PRODUCT ID) – One side.
- Input Data (PRODUCT ID) – Many side.

Created a separate Calendar table using DAX containing:
- Year
- Month
- Month Number
- Quarter
- Year Month

This supports time-based analysis and time intelligence calculations.

## 📐 DAX Measures & Calculations
### Calculated Columns
- Product Name
- Category
- Selling Price
- Buying Price
- Gross Sales
- Discount Amount
- Net Sales
- Total Cost
- Profit

### DAX Measures
- Total Sales
- Total Gross Sales
- Total Profit
- Total Cost
- Total Quantity
- Total Transactions
- Profit Margin %
- Average Selling Price
- Average Discount
- Total Discount
- YTD Sales
- Previous Year Sales
- Year-over-Year Growth %
- Product Sales Rank
- Sales Contribution %

## 📊 Dashboard Features & Visualizations

The dashboard includes the following visuals:

| Visualization | Purpose |
|---|---|
| KPI Cards | Total Sales, Total Profit, Units Sold, Profit Margin |
| Line Chart | Monthly Sales Trend |
| Bar Chart | Category-wise Sales |
| Column Chart | Top 10 Products by Sales |
| Donut Chart | Sales by Sale Type |
| Pie Chart | Sales by Payment Mode |
| Column Chart | Profit by Category |
| Slicers | Year, Date, Category, Sale Type, Payment Mode |

## 🎛️ Interactive Dashboard Features

- Year-wise sales filtering.
- Date range selection.
- Category-wise analysis.
- Sales type filtering.
- Payment mode filtering.
- Dynamic KPI updates based on slicer selections.

## 💡 Key Business Questions

The dashboard helps answer the following questions:

1. What is the overall sales revenue?
2. Which product category generates the highest sales?
3. Which products generate the highest profit?
4. Which sales type contributes the most revenue?
5. Which payment mode is most frequently used?
6. Which month has the highest sales?
7. How do discounts affect profitability?
8. How does sales performance compare across years?

## 📈 Business Insights

The dashboard can be used to identify:

- Best-performing product categories.
- High-revenue and high-profit products.
- Monthly and yearly sales patterns.
- Sales channel performance.
- Payment mode preferences.
- Products and categories with lower profitability.

## 🚀 Project Outcome

Developed an interactive Power BI Sales Performance Dashboard to transform raw sales data into meaningful business insights. The project demonstrates practical knowledge of data analytics, Power Query, data modeling, DAX, and business intelligence reporting.

**Skills:** Power BI | SQL | Python | Excel | DAX | Data Visualization
