📘 SQL Bookstore Analysis
🧾 Project Overview

This project focuses on analyzing a bookstore’s data using SQL.
It involves designing relational tables, importing datasets, and performing both basic and advanced SQL queries to uncover insights about books, customers, and orders.

Through this project, I practiced real-world SQL concepts like joins, aggregations, subqueries, and grouping to draw meaningful business insights from structured data.

🗂️ Project Structure
SQL-Bookstore-Analysis/
│
├── data/
│   ├── Books.csv
│   ├── Customers.csv
│   └── Orders.csv
│
├── queries/
   └── bookstore_analysis.sql

🧰 Tools & Technologies

SQL (PostgreSQL)

CSV datasets

Relational Database Concepts

🧱 Database Design

Books Table

Column	Type	Description
Book_ID	SERIAL PRIMARY KEY	Unique identifier for each book
Title	VARCHAR(100)	Book title
Author	VARCHAR(100)	Author name
Genre	VARCHAR(50)	Book category
Published_Year	INT	Year of publication
Price	NUMERIC(10,2)	Book price
Stock	INT	Available stock

Customers Table

Column	Type	Description
Customer_ID	SERIAL PRIMARY KEY	Unique identifier for each customer
Name	VARCHAR(100)	Customer name
Email	VARCHAR(100)	Customer email
Phone	VARCHAR(15)	Contact number
City	VARCHAR(50)	City of residence
Country	VARCHAR(150)	Country of customer

Orders Table

Column	Type	Description
Order_ID	SERIAL PRIMARY KEY	Unique identifier for each order
Customer_ID	INT	Linked to Customers table
Book_ID	INT	Linked to Books table
Order_Date	DATE	Date of order
Quantity	INT	Books purchased
Total_Amount	NUMERIC(10,2)	Total purchase amount
🔍 Key SQL Queries

Basic Queries-----

Retrieve all books in the “Fiction” genre

Find books published after the year 1950

Show orders placed in November 2023

Find customers from Canada

Calculate total stock and total revenue

Advanced Queries-----

Total books sold by genre

Average price of books by genre

Customers who placed more than 2 orders

Most frequently ordered book

Top customers by total spending

Remaining stock after all orders

📈 Insights Derived

Identified top-selling genres and authors

Analyzed customer purchase patterns by country and city

Calculated total revenue and remaining inventory

Determined high-value customers and frequently ordered books

👤 Author

Aadi Chauhan
🎓 Post Graduate in Statistics | Aspiring Data Analyst
🛠️ Skills: SQL | Power BI | Excel | Python
