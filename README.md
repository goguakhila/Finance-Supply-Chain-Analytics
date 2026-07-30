# Finance & Suppy Chain Analytics using SQL

##  Project Overview

This project focuses on analyzing financial and supply chain performance using SQL. It leverages advanced SQL techniques to identify top-performing customers, products, and markets, evaluate forecast accuracy, and generate actionable business insights that support data-driven decision-making.

##  Project Objectives

- Analyze sales performance across customers, products, and markets.
- Evaluate forecast accuracy using actual vs. forecasted quantities.
- Measure profitability and supply chain efficiency.
- Automate business reporting using reusable SQL components.
- Generate meaningful insights to support business decisions.

##  Tech Stack

- SQL
- MySQL
- MySQL Workbench

##  Database Tables

- dim_customer
- dim_product
- fact_sales_monthly
- fact_forecast_monthly
- fact_gross_price
- fact_manufacturing_cost
- fact_pre_invoice_deductions

##  Advanced SQL Concepts Used

This project demonstrates practical SQL skills by solving real-world business problems using advanced SQL concepts.

### 🔹 Common Table Expressions (CTEs)
Used to simplify complex queries by breaking them into logical steps, making analytical queries easier to read and maintain.

### 🔹 Subqueries
Used to perform calculations and comparisons within queries, enabling detailed business analysis such as forecast accuracy evaluation.

### 🔹 Views
Created reusable query layers to simplify reporting and improve query efficiency.

### 🔹 Built-in SQL Functions
Used aggregate, string, date, and numeric functions to perform calculations, transform data, and generate business metrics.

### 🔹 Stored Procedures
Developed reusable stored procedures to automate business reports and frequently performed analytical tasks.

### 🔹 Window Functions
Applied functions such as `DENSE_RANK()` to rank products, customers, and markets based on sales performance.

### 🔹 Joins & Aggregations
Combined multiple business tables using joins and aggregation functions to generate meaningful analytical reports.

##  Key Business Insights

- Identified the Top 3 products by quantity sold within each division.
- Ranked top-performing customers based on net sales.
- Analyzed sales performance across different markets.
- Calculated forecast accuracy for customers and markets.
- Measured forecast errors to evaluate planning efficiency.
- Generated reusable reports using Views and Stored Procedures.
- Enabled data-driven financial planning and supply chain optimization.

##  Project Structure

```
Finance-and-Supply-Chain-Analytics/
│── SQL Scripts/
│── Views/
│── Stored Procedures/
│── Reports/
│── Dataset/
└── README.md
```

##  Future Enhancements

- Build an interactive Power BI dashboard.
- Create automated monthly reporting procedures.
- Optimize SQL queries for large datasets.
- Add additional KPIs for financial and supply chain analysis.

If you found this project useful, feel free to ⭐ the repository.

