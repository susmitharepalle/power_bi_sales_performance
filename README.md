# power_bi_sales_performance
# Simple Sales Dashboard – Superstore Sales Analysis

## Overview
This dashboard presents an **interactive view of Superstore's sales performance**, highlighting trends, top-performing categories, customer segments, and delivery modes.  
It was built in **Power BI** using the `Superstore_Sales.csv` dataset to support data-driven decision-making.

---

## Tools & Technologies
- **Power BI** – Data visualization and dashboard design
- **Dataset** – Superstore Sales data  
  *(Columns: Order Date, Region, Category, Sub-Category, Segment, Sales, Profit, Quantity, Payment Mode, Ship Mode)*

---

## Dataset Preparation
1. **Data Import** – Loaded CSV file into Power BI.
2. **Date Formatting** – Converted `Order Date` into `Month-Year` format for trend analysis.
3. **Data Cleaning** – Ensured correct data types for numeric and text fields.
4. **Measures & KPIs**:
   - Total Sales
   - Total Profit
   - Total Quantity Sold
   - Average Delivery Time

---

## Dashboard Features
1. **KPIs**
   - **Total Sales**: 1.57M
   - **Total Profit**: 175.29K
   - **Total Quantity Sold**: 22K
   - **Average Delivery Time**: 3.93 days

2. **Donut Charts**
   - **Sales by Segment** – Shows sales distribution among Consumer, Corporate, and Home Office segments.
   - **Sales by Payment Mode** – Highlights sales share of COD, Online, and Card payments.

3. **Line Charts**
   - **Monthly Profits (YoY)** – Compares profit trends across 2019 and 2020.
   - **Monthly Sales (YoY)** – Tracks sales patterns over the years.

4. **Bar Charts**
   - **Sales by Ship Mode** – Standard Class leads with 0.91M in sales.
   - **Sales by Category** – Office Supplies leads with 0.64M sales.
   - **Sales by Sub-Category** – Phones lead with 0.20M sales, followed by Chairs (0.18M) and Binders (0.17M).

---

## Key Insights
1. **Office Supplies category** is the top revenue generator at **0.64M**, followed by Technology (0.47M) and Furniture (0.45M).
2. **Standard Class shipping** dominates sales delivery, accounting for **over 58% of total sales**.
3. **Phones** are the highest-selling sub-category, generating **0.20M** in sales.
4. **Profit trends** show notable peaks in March and November, suggesting seasonal buying patterns.

---

##Export
- Dashboard is available as:
  - `.pbix` file for interactive exploration
  - PDF export for quick review
