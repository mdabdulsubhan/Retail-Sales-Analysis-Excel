# KPI Definitions

## Retail Sales Performance & Executive Decision Support System

**Version:** 1.0  
**Role:** Data Analyst  
**Tool:** Microsoft Excel

---

## Purpose

This document defines the Key Performance Indicators (KPIs) used in the Executive Dashboard.

Each KPI is defined based on its business meaning, calculation logic, business purpose and decision supported.

---

## KPI Catalogue

| KPI | Business Definition | Calculation Logic | Business Purpose |
|---|---|---|---|
| Total Sales | Total revenue generated from all orders | `SUM(Sales)` | Measure overall business growth |
| Total Profit | Total profit generated from sales | `SUM(Profit)` | Monitor profitability |
| Profit Margin % | Profit expressed as a percentage of sales | `Profit / Sales` | Evaluate business efficiency |
| Total Orders | Total number of completed orders | `COUNT(Order ID)` | Monitor demand |
| Average Order Value | Average revenue generated per order | `Sales / Orders` | Understand customer spending |
| Total Customers | Number of unique customers | `UNIQUE(Customer ID)` | Monitor customer base |
| Top Category | Category generating the highest revenue | Pivot Table / Analysis | Evaluate product performance |
| Top Region | Region generating the highest revenue | Pivot Table / Analysis | Evaluate regional performance |
| Average Discount | Average discount offered on sales | `AVERAGE(Discount)` | Monitor pricing and discount levels |
| Shipping Cost | Total shipping expense | `SUM(Shipping Cost)` | Monitor operational and logistics cost |

---

## KPI Business Purpose

### Total Sales

Measures the total revenue generated from all orders and provides an overall view of business performance.

### Total Profit

Measures the total profit generated and helps management monitor profitability and cost performance.

### Profit Margin %

Shows profit as a percentage of sales and helps evaluate pricing and business efficiency.

### Total Orders

Measures the number of completed orders and provides an indication of customer demand.

### Average Order Value

Measures the average revenue generated per order and helps understand customer spending behaviour.

### Total Customers

Measures the unique customer base and supports customer analysis and retention planning.

### Top Category

Identifies the product category generating the highest revenue and supports product and inventory decisions.

### Top Region

Identifies the region generating the highest revenue and supports regional planning.

### Average Discount

Measures the average discount applied to sales and helps evaluate pricing and discount policy.

### Shipping Cost

Measures total shipping expense and supports logistics and operational cost analysis.

---

## KPI Design Principles

The dashboard follows these principles:

- Every KPI should answer a business question.
- KPIs should update automatically after data refresh.
- KPI values should be validated against source data.
- KPIs should be displayed clearly using cards, charts or tables.
- KPI calculations should remain consistent across the dashboard.

---

## Dashboard KPI Areas

The primary executive KPI cards include:

- Total Sales
- Total Profit
- Profit Margin
- Total Orders
- Total Customers
- Average Order Value
- Average Discount

Additional analytical KPIs can be used within supporting dashboard areas where required.
