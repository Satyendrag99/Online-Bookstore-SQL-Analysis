# Online Bookstore SQL Analysis

## 📊 Project Overview
This project is based on an Online Bookstore database designed using MySQL.

The objective of this project was to analyze bookstore sales, customer behavior, inventory management, and revenue generation using SQL queries.

This project demonstrates practical SQL skills used in real-world business analytics scenarios.

---

## ❗ Problem Statement
Online bookstores generate large amounts of transactional data, but without proper analysis it becomes difficult to:

- Track best-selling books
- Identify top customers
- Monitor low stock inventory
- Analyze monthly sales trends
- Understand customer purchasing behavior
- Calculate revenue and business growth

The goal of this project was to solve these business problems using SQL queries and data analysis techniques.

---

## ✅ Solution Implemented
A relational database system was created with three main tables:

- Books
- Customers
- Orders

Using SQL operations like:

- JOIN
- GROUP BY
- ORDER BY
- Aggregate Functions
- Subqueries
- HAVING Clause
- LIMIT & OFFSET
- Date Functions

Business insights were generated from the bookstore data.

---

## 🗂 Database Schema

### 📚 Books Table
Stores book information:
- Book ID
- Title
- Author
- Genre
- Price
- Stock

### 👤 Customers Table
Stores customer details:
- Customer ID
- Name
- Email
- City
- Country

### 🧾 Orders Table
Stores transaction data:
- Order ID
- Customer ID
- Book ID
- Quantity
- Order Date
- Total Amount

---

## 📈 Key Business Insights Generated

### 📊 Sales Analysis
- Monthly sales reports generated to track business growth
- Revenue calculated for each book
- Top-selling genres identified

### 👥 Customer Analysis
- Most valuable customers identified based on lifetime spending
- Customers with multiple orders analyzed
- Customers with no orders detected

### 📦 Inventory Management
- Low stock books identified for restocking
- Remaining stock after order fulfillment calculated

### 📚 Product Performance
- Most frequently ordered books identified
- Highest priced books in each genre analyzed

---

## 🧠 SQL Concepts Used
- DDL & DML Commands
- Aggregate Functions
- INNER & LEFT JOIN
- GROUP BY & HAVING
- Subqueries
- ORDER BY
- LIMIT & OFFSET
- Date Functions (DATE_FORMAT)

---

## 🔍 Example Insights

### ⭐ Top Selling Genre
Identified the genre with maximum quantity sold.

### 📅 Monthly Sales Report
Generated month-wise revenue analysis using DATE_FORMAT().

### 💰 Most Valuable Customer
Calculated customer lifetime value using SUM(Total_Amount).

### ⚠️ Low Stock Alert
Detected books with stock less than 5.

---

## 🛠 Technologies Used
- MySQL
- SQL
- MySQL Workbench

---

## 🎯 Learning Outcomes
Through this project, I learned:

- Database schema design
- Writing optimized SQL queries
- Business data analysis using SQL
- Customer analytics
- Inventory management analysis
