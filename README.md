
# 📊 Sales Performance Dashboard

## 📌 Project Overview

This project analyzes sales performance data to provide actionable business insights using Excel, SQL, Python, and Power BI. The dashboard helps stakeholders track revenue, profit, customer behavior, product performance, and regional sales trends.

---

## 🎯 Objectives

- Monitor overall sales performance
- Identify top-performing products and categories
- Analyze regional sales trends
- Track customer purchasing behavior
- Measure profit and revenue growth
- Support data-driven business decisions

---

## 🛠️ Tools & Technologies

- Power BI
- Microsoft Excel
- SQL (MySQL)
- Python (Pandas, NumPy, Matplotlib, Seaborn)


---

## 📂 Project Structure

```
Sales-Performance-Dashboard/
│
├── Dataset/
│   └── SuperStore Sales DataSet.xlsx
│
├── Dashboard/
│   └── Sales_Dashboard.pbix
│
├── Images/
│   └── SalesDash1.jpg
    └── SalesDas2.jpg


## 📈 Dashboard Preview
Sales Performance Dashboard
<img width="891" height="502" alt="SalesDash1" src="https://github.com/user-attachments/assets/2800521e-61bc-476c-be27-bf6a802afdcc" />



Sales Forcasting

<img width="877" height="498" alt="SalesDas2" src="https://github.com/user-attachments/assets/1d0990ab-5186-468d-a24b-3ee901414324" />


---

## 📊 Key KPIs

- Total Sales
- Total Profit
- Total Orders
- Profit Margin %
- Average Order Value
- Customer Count

---

## 📌 Dashboard Features

### Executive Summary
- Total Revenue
- Total Profit
- Total Orders

### Sales Analysis
- Monthly Sales Trend
- Sales by Category
- Sales by Sub-Category

### Customer Analysis
- Top Customers
- Customer Segmentation
- Average Order Value

### Regional Analysis
- Sales by Region
- Profit by Region
- Top Performing States

### Product Analysis
- Best Selling Products
- Most Profitable Products

---

## 🐍 Python Analysis

Performed:
- Data Cleaning
- Missing Value Treatment
- Exploratory Data Analysis (EDA)
- Sales Trend Analysis
- Profitability Analysis

### Sample Python Code

```python
import pandas as pd

df = pd.read_excel("SuperStore Sales DataSet.xlsx")

total_sales = df["Sales"].sum()
total_profit = df["Profit"].sum()

print("Total Sales:", total_sales)
print("Total Profit:", total_profit)
```

---

## 🗄️ SQL Analysis

### Total Sales

```sql
SELECT SUM(Sales) AS Total_Sales
FROM sales_data;
```

### Sales by Category

```sql
SELECT Category,
       SUM(Sales) AS Revenue
FROM sales_data
GROUP BY Category
ORDER BY Revenue DESC;
```

### Top 10 Customers

```sql
SELECT Customer_Name,
       SUM(Sales) AS Total_Sales
FROM sales_data
GROUP BY Customer_Name
ORDER BY Total_Sales DESC
LIMIT 10;
```

---

## 🔍 Insights Generated

- Technology category generated the highest revenue.
- Western region contributed the maximum sales.
- A small percentage of customers generated a significant share of revenue.
- Sales peaked during the festive season.
- Some high-sales products had low profit margins.

---

## 🚀 Business Impact

This dashboard enables businesses to:

- Improve sales strategies
- Identify profitable products
- Optimize inventory planning
- Enhance customer retention
- Increase overall profitability

---


⭐ If you found this project useful, consider giving it a star!
