# Optimizing Financial Analytics with SQL

## 📌 Project Overview
This project focuses on optimizing financial analytics for **AtliQ Hardware**, a global computer hardware manufacturer. The company previously relied on large Excel files, which led to inefficiencies in data analysis. By migrating to **MySQL**, the project enhanced performance, scalability, and overall data accessibility.
- The Dataset contain more than 1 million records.

### 🔍 Business Context
- AtliQ Hardware operates in **APAC, EU, NA, and LATAM** markets, offering high-performance computer components.
- The finance team struggled with **slow processing times** due to large, unstructured Excel files.
- The solution was to **migrate financial data analytics to MySQL**, enabling faster queries and better data management.

## 🚀 Key Challenges & Solutions
| Challenge | Solution |
|-----------|----------|
| **Slow Performance with Excel** | Replaced Excel with **MySQL database** for structured storage and faster queries. |
| **Expanding Data Analytics Team** | Developed **custom SQL functions, stored procedures, and views** to streamline financial reporting. |
| **Query Optimization** | Optimized query execution time by: <br> 1️⃣ Creating a `dim_date` table to remove redundant function calls. <br> 2️⃣ Storing `fiscal_year` in the `fact_sales_monthly` table for quicker lookups. |

## 🔢 Key SQL Techniques Used
✅ **Advanced Joins & Aggregations** – Integrated multiple tables for detailed financial analysis.  
✅ **Stored Procedures** – Automated monthly **Gross Sales Reports** for different customers.  
✅ **Views & CTEs** – Created modular reports for **pre-invoice and post-invoice deductions**.  
✅ **Window Functions (OVER Clause)** – Analyzed customer-wise **net sales distribution per region**.

## 📊 Key Reports & Insights Generated
📌 **Gross Sales Report** – Monthly sales breakdown for individual products.  
📌 **Top Customers, Products, and Markets** – Identified high-performing business segments.  
📌 **Net Invoice Sales** – Incorporated **pre-invoice and post-invoice discounts** for precise revenue tracking.  
📌 **Market-Based Sales Analysis** – Developed a **stored procedure** to fetch top-performing customers per market.


