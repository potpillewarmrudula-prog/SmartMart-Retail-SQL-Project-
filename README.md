# SmartMart Retail SQL Project

## Retail Sales & Customer Intelligence Analytics

This project uses **MySQL** to build a retail database and perform sales, customer, product, and employee analysis using SQL.

## Project Objective

The goal is to analyze SmartMart's retail data and answer important business questions related to:

- Customer behavior and spending
- Product and category performance
- Sales and revenue trends
- Employee performance
- High-value customers and orders
- Revenue concentration
- Business performance over time

## Database

**Database:** `smartmart_retail_sql_project`

The project contains 5 main tables:

- `customers` — customer information, location, registration, and segments
- `employees` — employee details, department, joining date, and salary
- `products` — product, category, brand, price, and status
- `orders` — customer orders, employees, dates, status, and payment mode
- `order_items` — products purchased, quantity, discounts, and line totals

## Data Generation

The project includes a MySQL data-generation script that creates approximately:

| Table | Records |
|---|---:|
| Customers | 20,000 |
| Employees | 2,000 |
| Products | 5,000 |
| Orders | 20,000 |
| Order Items | 40,000 |

The dataset is generated using **MySQL 8.0+**, including recursive CTEs, constraints, foreign keys, and indexes.

## SQL Analysis Performed

### Customer Analysis

- Total customer count
- City-wise customer distribution
- Top customers by revenue
- Repeat customer analysis
- Customers with no purchases
- Customer spending segmentation

### Product Analysis

- Top products by revenue
- Top products by quantity sold
- Products never sold
- Category-wise revenue
- Low-performing products
- Product ranking within categories

### Sales Analysis

- Total revenue
- Monthly revenue
- Quarterly revenue
- Average order value
- High-value orders
- Running revenue
- Month-over-month revenue change

### Employee Analysis

- Employee revenue contribution
- Top-performing employees
- Employees with no sales
- Customer revenue concentration using Pareto-style grouping

## Advanced SQL Concepts Used

This project demonstrates:

- `SELECT`
- `WHERE`
- `GROUP BY`
- `HAVING`
- `ORDER BY`
- `LIMIT`
- Aggregate functions
- `INNER JOIN`
- `LEFT JOIN`
- Subqueries
- CTEs
- `CASE`
- Window functions
- `DENSE_RANK()`
- `NTILE()`
- `LAG()`
- Running totals
- Views
- Stored procedures
- Indexes
- `UNION`
- `UNION ALL`
- Primary keys
- Foreign keys
- Constraints

## Project Files

```text
SmartMart-Retail-SQL-Project/
│
├── SmartMart_Data_Generation.sql
├── SmartMart_Analysis.sql
└── README.md
```

## How to Run

1. Open **MySQL Workbench**.
2. Open `SmartMart_Data_Generation.sql`.
3. Execute the complete script to create the database, tables, indexes, and sample data.
4. Open `SmartMart_Analysis.sql`.
5. Make sure the database is selected:
   ```sql
   USE smartmart_retail_sql_project;
   ```
6. Run the analysis queries.

## Project Workflow

```text
Database Creation
       ↓
Table Creation
       ↓
Data Generation
       ↓
Data Validation
       ↓
Customer Analysis
       ↓
Product Analysis
       ↓
Sales Analysis
       ↓
Employee Analysis
       ↓
Advanced SQL Analysis
       ↓
Business Insights
```

## Author

**Mrudula Potpillewar**

BCA Graduate | MCA Student | Data Analytics & AI Learner

**Skills:** Python | SQL | Excel | Power BI | Tableau | Data Visualization
