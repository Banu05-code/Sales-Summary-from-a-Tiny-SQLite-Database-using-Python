Basic Sales Summary using SQLite and Python
📌 Overview
This project demonstrates how to build a simple sales analytics pipeline using:

SQLite for data storage

SQL for querying

Pandas for data handling

Matplotlib for visualization

You’ll learn how to connect to a local SQLite database, run basic SQL queries, load the results into a DataFrame, and visualize the sales summary using a bar chart.

📂 Project Structure
sales_data.db – SQLite database file containing a single sales table

sales_summary.py – Python script that:

Connects to the database

Runs SQL queries to summarize sales data

Prints results using print()

Visualizes revenue by product using a bar chart

(Optional) sales_chart.png – Saved version of the bar chart

⚙️ How It Works
Database Creation:
A small in-memory or file-based SQLite database is created with a table called sales.

Data Insertion:
Sample rows are inserted with columns: product, quantity, and price.

SQL Querying:
Using SQL, the script calculates:

Total quantity sold per product

Total revenue per product (quantity × price)

Data Analysis & Visualization:

The query result is loaded into a Pandas DataFrame.

Revenue is plotted as a bar chart grouped by product.

🔧 Requirements
Python 3.x

Libraries:

sqlite3 (built-in)

pandas

matplotlib

Install extras with:
pip install pandas matplotlib

📊 Sample Output
Console output:

  product  total_qty  revenue
0  Apples         16      8.0
1 Bananas         14      4.2
2 Oranges         15     10.5

Bar chart: Revenue for each product.


