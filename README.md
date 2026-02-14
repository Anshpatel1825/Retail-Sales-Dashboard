# Retail Sales Dashboard | SQL + Power BI

## Project Overview

This project analyzes retail sales data using SQL and Power BI to build an interactive business intelligence dashboard.

The dashboard provides meaningful insights into:

- Total Sales, Total Profit, and Total Orders
- Sales Trend Over Time (Monthly Performance)
- Profit by Product Category
- Sales by Customer Type
- Shipping Mode Analysis
- Profit by State
- Discount Impact on Profitability

The goal of the project is to transform raw sales data into clear, actionable insights for business decision-making.

---

## Objective

- Understand overall business performance through key KPIs
- Identify the most profitable product categories
- Analyze customer segments and buying behavior
- Evaluate the impact of discounts on profit
- Compare shipping modes and delivery patterns
- Provide insights that support data-driven decisions

---

## Dataset

- **Total Records:** 4,925 orders

**Attributes Include:**  
Order Date, Customer Name, City, State, Customer Type,  
Product Name, Product Category, Order Quantity,  
Sub Total, Discount %, Discount, Order Total,  
Shipping Cost, Delivery Days, Total, Total Profit Per Order

---

## Data Cleaning (Excel Phase)

Before analysis, the dataset was cleaned using Microsoft Excel:

- Checked for missing values
- Corrected data formatting
- Ensured numeric columns were valid
- Verified calculation fields
- Removed inconsistent or incomplete records

This step ensured accuracy and reliability for SQL analysis and dashboard creation.

---

## SQL Integration (Analysis Proof for Interviews)

The cleaned CSV file was imported into SQL under the table:

**Table Name:** `retail_sales`

### Key SQL Queries Used

**1️⃣ Total Sales**

```sql

SELECT SUM([Total Profit Per Order]) AS total_profit
FROM retail_sales;



