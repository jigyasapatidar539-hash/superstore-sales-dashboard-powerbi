# Superstore Sales Dashboard (Power BI)

Interactive sales analytics dashboard built using MySQL and Power BI Desktop, analyzing the Superstore Sales dataset.

## 📊 Overview
This project demonstrates an end-to-end data analytics workflow — from raw CSV data to a fully interactive business intelligence dashboard.

## 🛠️ Tools & Technologies
- **MySQL** — data storage and querying
- **Power BI Desktop** — data visualization and dashboard building

## ✨ Features
- Sales trend over time (line chart)
- Category-wise sales breakdown (pie chart)
- City-wise top performing locations (bar chart)
- Region-based interactive filtering (slicer)
- KPI card showing total sales

## 📈 Key Insights
- Furniture category contributes the highest share of total sales
- Los Angeles and Philadelphia are top-performing cities by sales
- Sales show a declining trend over the observed period

## Phase 2: Customer Segmentation (K-Means)
Performed RFM analysis (Recency, Frequency, Monetary) and applied K-Means 
clustering to segment customers into actionable groups.

**Segments identified:**
- High Value Customers — frequent, recent, high spenders
- At Risk Customers — long time since last purchase
- New Customers — recent but low frequency
- Regular Customers — moderate across all metrics

**Tools:** Python, Pandas, Scikit-learn, Matplotlib

## Phase 3: Sales Forecasting (Linear Regression)
Built a time-series forecasting model to predict future monthly sales trends 
using historical Superstore sales data.

**Approach:**
- Aggregated daily transactions into monthly sales totals
- Applied Linear Regression to capture overall sales trend
- Forecasted sales for the next 6 months

**Tools:** Python, Pandas, Scikit-learn, Matplotlib

## 📁 Files
- `sales data.pbix` — Power BI dashboard file

## 👩‍💻 Author
Jigyasa Patidar — B.Tech AI & Data Science student
