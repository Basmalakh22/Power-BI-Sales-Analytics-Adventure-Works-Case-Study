# AdventureWorks Sales & Customer Analytics Dashboard

## 📊 Project Overview

An advanced, interactive Power BI dashboard designed to analyze **AdventureWorks'** sales performance, customer behavior, and regional insights. This project integrates advanced Power BI features and delivers actionable recommendations for stakeholders.

---

## 🎯 Objectives

- Analyze sales performance by time period and region.
- Discover customer behavior patterns and profit contribution.
- Track product and market trends.
- Assess operational efficiency, including shipping and seasonal performance.

---

## 📦 Deliverables

- ✅ Power BI Report (.pbix) with rich interactivity and visuals.
- ✅ Documentation (3-5 pages) covering methodology, insights, DAX logic, and advanced features.
- ✅ Presentation (5–10 slides) summarizing key findings and strategic recommendations.

---

## ❓ Business Questions Addressed

### 1. Sales Performance

- Total sales across time (year, quarter, month, week, day).
- Top-performing products and categories.
- Revenue-driving regions.

### 2. Customer Insights

- Top 100 customers by number of orders.
- Order trends by income level and occupation.
- Profit-generating customers.

### 3. Product & Market Trends

- Best-selling products and categories.
- Profit margin analysis.
- Price impact on profit.

### 4. Operational Efficiency

- Average Order Value (AOV) trends.
- Seasonal sales patterns.
- Regional shipping performance.

---

## 🧹 Data Preparation

### Imported Tables

- `Sales Data`
- `Returns Data`
- `Customers`
- `Products`
- `Product Subcategories`
- `Product Categories`
- `Territory`
- `Date Table`

### Transformation Highlights (Power Query)

- Cleaned duplicates and nulls.
- Standardized date formats.
- Merged customer name fields.
- Enhanced `Date Table` with:
  - Year, Quarter, Month, Month Name
  - Start of Week (Saturday), Day

---

## 📐 Data Model: Galaxy Schema

### Fact Tables

- `Sales Data`
- `Returns Data`

### Dimension Tables

- `Customers`, `Products`, `Product Subcategories`, `Product Categories`, `Territory`, `Date Table`

### Relationships

- One-to-Many links between dimension tables and fact tables as required.

---

## 🧠 Key DAX Measures

- `Total Revenue`, `YTD Revenue`, `Previous Month Revenue`, `Revenue Target`
- `Average Revenue`, `Average Retail Price`, `Adjustment Price`
- `Adjustment Revenue`, `Total Orders`, `Return Rate`
- `Total Profit`, `Adjustment Profit`, `Previous Month Profit`, `Profit Target`
- `Top Customer by Revenue`, `Top 100 Customers`, etc.

---

## 🧩 Dashboard Pages

### 1. Executive Summary

- KPIs: Revenue, Orders, Returns (monthly)
- Sales Trends (line chart drillable from year to day)
- Product & Category performance
- Return Analysis

### 2. Regional Performance

- Country-level orders (map)
- Continent slicer

### 3. Product Details (Drill-through)

- Orders, Revenue, Profit vs Target (gauges)
- Profit & Order Trends
- Field Parameters & Numeric Inputs (Optional)

### 4. Customer Insights

- Revenue per Customer
- Trends by Income & Occupation
- Top 100 Customers table
- Top Customer stats (cards)

---

## 💡 Advanced Features

- ✅ **Drill-Through Pages**
- ✅ **Field Parameters** (Orders, Profit, Returns, etc.)
- ✅ **Numeric Parameters** (Price Adjustment slider)
- ✅ **Custom Tooltips**
- ✅ **Bookmarks & Navigation Buttons**
- ✅ **Icons & User-Friendly Design**
- ✅ **Row-Level Security (Optional)**

---

## 🛠 Tools Used

- **Microsoft Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**

---
