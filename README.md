# Task 7: Basic Sales Summary Using SQLite and Python

## Overview

This project demonstrates how to use Python to connect to a SQLite database, query basic sales data, and visualize the results. The goal is to understand how to retrieve total quantity sold and total revenue per product from a small sales database, then display the results in both text and graphical forms.

## Features

- Creates a SQLite database (sales_data.db) with a sales table
- Inserts sample sales data for products like Laptop, Smartphone, and Tablet
- Executes SQL queries to calculate total sales quantity and revenue per product
- Displays the results using Pandas in tabular format
- Creates and saves a bar chart showing total revenue per product using Matplotlib

## Technologies Used

- Python
- SQLite (via `sqlite3` library)
- Pandas (data manipulation)
- Matplotlib (data visualization)
- Jupyter Notebook

## How to Run

1. Open `Task7.ipynb` in Jupyter Notebook.
2. Run all cells sequentially.
3. The notebook will create the database, insert sample data, perform queries, print results, and display/save a bar chart of revenues.

## Project Files

- `Task7.ipynb`: Jupyter Notebook with all coding steps and outputs
- `sales_data.db`: Generated SQLite database file
- `sales_revenue_chart.png`: Saved revenue bar chart image (created when running notebook)

## Usage

This project is ideal for beginners to learn how SQL databases interact with Python, how to run queries, and visualize simple data analytics results.

## Author
Boddupally Kavya

## License

This project is licensed under the MIT License.
