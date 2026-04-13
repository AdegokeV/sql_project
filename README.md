# sql_project
# 🧾 SQL Sales & Order Management Database Project

## Overview

A concise **relational database** for managing a sales workflow (customers, orders, products, and employees) built to demonstrate practical SQL design and querying.

## Objective

* Design a normalized schema
* Model core business entities
* Enable fast, insight-driven queries

## Core Tables

* **Customers** – customer info
* **Orders** – order records (dates, customer, employee)
* **OrderDetails** – items, quantity, price, discount
* **Products** – product data, stock, pricing
* **Categories** – product grouping
* **Suppliers** – supplier details
* **Employees** – staff managing orders

## SQL Skills

* DDL: `CREATE DATABASE`, `CREATE TABLE`
* Keys & structure (primary keys)
* Data types (`INT`, `VARCHAR`, `DATE`, `FLOAT`)
* DML: `INSERT`, `SELECT`
* Relational modeling (table relationships)

## Example Questions

* Top customers by orders/revenue
* Best-selling products
* Sales trends over time
* Orders handled per employee

## Run

```sql
CREATE DATABASE sql_project;
USE sql_project;
```

Execute the script in SSMS (or any SQL tool), then run queries.

## Highlights

* Clean, scalable schema
* Real-world sales model
* Ready for analytics extensions

## Next Steps

* Add foreign keys
* Include sample data
* Build analytical queries/dashboards

---
