# SQL Checkpoint - Northwind Traders Database

## Overview

This checkpoint is designed to assess proficiency in Structured Query Language (SQL). The task involves querying the Northwind Traders database to retrieve, filter, sort, and join tables.

## Key Learning Objectives

- Reading an Entity Relationship Diagram (ERD)
- Writing queries to return specific columns from a SQL database
- Filtering rows using SQL conditions
- Sorting records in descending order
- Joining multiple tables to extract meaningful insights

## Database Schema

The Northwind Traders database contains multiple tables. The primary tables used in this checkpoint are:

- **Product**: Stores information about products sold by Northwind Traders.
- **Order**: Contains high-level order details.
- **Shipper**: Stores information about shipping companies.

## Setup Instructions

1. Ensure you have **Python**, **SQLite3**, and **Jupyter Notebook** installed.
2. Load the `Northwind.sqlite` database in Jupyter Notebook.
3. Run the provided SQL queries within the notebook to complete the checkpoint.
4. Submit the completed notebook via CodeGrade.

## Tools Used

- **SQLite3** for database interaction
- **Pandas** for data manipulation
- **Jupyter Notebook** for executing SQL queries within Python

## Assignment Tasks

The checkpoint consists of five tasks:

### 1. Select an Entire Table

Retrieve all columns and rows from the `Product` table.

```sql
```

### 2. Select All Columns and Filter Rows

Retrieve all columns from the `Product` table where discontinued has a value of 1.

```sql
```

### 3. Select a Single Column with Two Conditions

Retrieve the `ProductName` where the product is **out of stock** and **not discontinued**.

```sql
```

### 4. Sort in Descending Order & Return Top Five Rows

Retrieve the `ProductName` and `UnitPrice`, sorting by `UnitPrice` in descending order, and return only the top five results.

```sql
```

### 5. Join Two Tables & Filter Results

Retrieve the name and phone number of shippers who have charged more than \$1000 for shipping cost. Join the `Shipper` and `Order` tables.

```sql
```

## Conclusion

This checkpoint reinforces SQL querying techniques essential for data analysis. It focuses on retrieving, filtering, sorting, and joining data efficiently. Mastering these concepts will enhance your database querying skills, preparing you for real-world data challenges.


