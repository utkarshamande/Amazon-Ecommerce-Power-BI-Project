# Amazon E-commerce Business Performance Dashboard

## Project Overview
This project is a Power BI dashboard created to analyze and visualize Amazon E-commerce sales data.  
The dashboard helps understand business performance, customer behavior, product sales, and delivery analysis using interactive visualizations.

This project is designed for:
- Data Analyst Fresher Resume
- Internship Portfolio
- Power BI Practice Project

---

# Tools & Technologies Used

- Power BI
- Python
- Pandas
- NumPy
- Jupyter Notebook
- CSV Dataset

---

# Project Workflow

## 1. Data Collection
Imported Amazon E-commerce sales dataset in CSV format.

---

## 2. Data Cleaning Using Python
Performed data cleaning using Pandas library.

### Cleaning Steps:
- Removed duplicate rows
- Fixed missing values
- Converted data types
- Converted date columns into datetime format
- Created new columns:
  - month
  - year
  - delivery_days
  - profit
  - profit_margin

---

## 3. Data Visualization in Power BI

Created 2 interactive dashboards.

---

# Dashboard 1 — Executive Sales Overview

### KPIs
- Total Revenue
- Total Profit
- Total Orders
- Total Customers

### Visualizations
- Monthly Revenue Trend
- Revenue by Category
- State-wise Revenue Distribution
- Revenue by Payment Method

### Filters
- Month
- Category
- State

---

# Dashboard 2 — Product & Customer Insights

### Visualizations
- Top 10 Revenue Generating Products
- Brand Performance Analysis
- Profit by Sub Category
- Revenue Contribution by Sub Category
- Average Delivery Time by State

### Filters
- Payment Method
- Category
- Month

---

# Key Business Insights

- Electronics category generated highest revenue.
- Top products contribute major sales share.
- UPI and Card payments are widely used.
- Delivery performance varies across states.
- Some sub-categories generate higher profits than others.

---

# Python Libraries Used

```python
import pandas as pd
import numpy as np
