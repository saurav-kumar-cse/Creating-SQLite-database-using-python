## Objective

This project demonstrates how to:
Create and interact with a SQLite database in Python
Perform basic SQL queries (aggregation, grouping)
Use Pandas for data loading and manipulation
Generate simple visualizations using Matplotlib

## ⚙️ Tools & Libraries
Python (3.x)
SQLite3 (built into Python)
Pandas
Matplotlib
Jupyter Notebook

## 🧠 Steps Performed
Connected to a local SQLite database (sales_data.db).
Created a sales table with fields: product, quantity, and price.
Inserted sample data for around 10–15 transactions.
Executed an SQL query to calculate:
Total quantity sold per product
Total revenue (quantity × price)
Loaded results into a Pandas DataFrame.
Displayed the summary using print statements.
Visualized the total revenue by product in a bar chart.
Saved outputs to CSV (sales_summary.csv) and PNG (sales_chart.png).

### Example Output
Console Output
Basic Sales Summary:

         product     total_qty   revenue
0         Laptop           8   486000.0
1        Monitor           4    48000.0
2       Headphones        12    28600.0
3        Keyboard         10    15000.0
4           Mouse         20    16000.0


### Bar Chart Output:
A simple bar chart (sales_chart.png) showing total revenue by product.
🚀 How to Run
Clone the repository or download the files.
Open sql_connect.ipynb in Jupyter Notebook.
Run all cells to:
Create the database
Execute SQL queries
Display and save the sales summary and chart
