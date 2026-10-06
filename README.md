# Online Bookstore SQL Analysis

## About the Project

This project focuses on analyzing an online bookstore database using **PostgreSQL** and SQL.

The database contains information about books, customers, and orders. The project includes basic and advanced SQL queries to answer different business-related questions.

## Database Structure

The database contains three main tables:

* **Books** – Book details, price, genre, publication year and stock
* **Customers** – Customer information and location
* **Orders** – Order details, quantity and total amount

## SQL Concepts Used

* SELECT
* WHERE
* DISTINCT
* ORDER BY
* LIMIT
* BETWEEN
* SUM()
* AVG()
* COUNT()
* GROUP BY
* HAVING
* INNER JOIN
* LEFT JOIN
* COALESCE()
* Primary Keys
* Foreign Keys

## Analysis Questions

Some of the questions answered in this project include:

1. Retrieve books from a specific genre
2. Find books published after a specific year
3. Find customers from a specific country
4. Retrieve orders from a specific date range
5. Calculate total book stock
6. Find the most expensive book
7. Calculate total revenue
8. Find total books sold by genre
9. Calculate the average price of Fantasy books
10. Find customers who placed at least two orders
11. Find the most frequently ordered book
12. Find the top 3 most expensive Fantasy books
13. Calculate books sold by each author
14. Find the cities of customers who spent over $30
15. Find the customer who spent the most
16. Calculate remaining stock after fulfilling orders

## Tools & Technologies

* PostgreSQL
* SQL
* pgAdmin 4

## Project Structure

```text
online-bookstore-sql-analysis/
│
├── README.md
│
├── sql/
│   └── online_bookstore.sql
│
└── data/
    ├── books.csv
    ├── customers.csv
    └── orders.csv
```

## How to Run

1. Install PostgreSQL.
2. Open pgAdmin 4 or another PostgreSQL client.
3. Create the database:

```sql
CREATE DATABASE online_bookstore;
```

4. Import the CSV files from the `data/` folder into their respective tables.
5. Open the `sql/online_bookstore.sql` file.
6. Run the SQL queries in PostgreSQL.

## Key Learning

This project helped me practice SQL for data analysis, including:

* Filtering and sorting data
* Aggregate functions
* Joining multiple tables
* Grouping and filtering grouped data
* Analyzing sales and revenue
* Customer and book analysis
* Stock analysis

