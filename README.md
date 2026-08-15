# Retail Sales Power BI Dashboard

## 📊 Project Overview

An interactive Power BI dashboard designed to analyze retail sales performance, profitability, product performance, and geographic sales trends.

The dashboard provides both an executive overview of the business and a detailed analysis of individual product performance.

---

## 🎯 Business Objectives

The main objectives of this project were to:

- Monitor overall sales and profitability
- Analyze revenue trends over time
- Compare revenue and profit across product categories
- Identify the strongest and weakest performing products
- Analyze sales performance by country
- Evaluate product profit margins
- Identify high-, medium-, and low-margin products
- Provide an interactive dashboard for business decision-making

---

## 🛠️ Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Data Visualization**

---

## 📌 Key Performance Indicators

The dashboard tracks several key business metrics:

| KPI | Result |
|---|---:|
| Total Revenue | €1.63M |
| Total Profit | €807.34K |
| Units Sold | 24K |
| Profit Margin | 49.50% |
| Total Orders | 12K |
| Total Customers | 2K |

---

## 📄 Dashboard Pages

### 1. Retail Sales Overview

The executive dashboard provides a high-level view of business performance.

It includes:

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Revenue Over Time
- Revenue by Category
- Profit by Category
- Profit Margin by Category
- Revenue by Country
- Top Performing Product

![Retail Sales Overview](retail-sales-overview.png)

---

### 2. Product Performance Analysis

The second page focuses on detailed product-level analysis.

It includes:

- Units Sold by Product
- Total Revenue by Product
- Profit Margin by Product
- Total Profit by Product
- Product Performance classification
- Revenue vs. Profit analysis

Products are classified into:

- 🟢 **High Margin**
- 🟡 **Medium Margin**
- 🔴 **Low Margin**

![Product Performance Analysis](product-performance-analysis.png)

---

## 💡 Key Insights

The dashboard highlights several important business insights:

- Total revenue reached approximately **€1.63M**.
- Total profit reached approximately **€807K**.
- The overall profit margin was approximately **49.5%**.
- **Leather Boots** generated the highest product revenue at approximately **€224K**.
- **Baseball Cap** achieved one of the highest product profit margins at approximately **60%**.
- **Leather Boots** generated high revenue but had a relatively low profit margin of approximately **44.3%**, highlighting the difference between sales volume and profitability.
- Spain generated the highest revenue among the countries shown in the dashboard. 
- Product performance varies considerably across products, making margin analysis important for business decisions.

---

## 🧮 DAX Measures

Several DAX measures were created to calculate the main business KPIs, including:

```DAX
Total Revenue = SUM(Sales[Revenue])
