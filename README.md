# Task 7: Get Basic Sales Summary from a Tiny SQLite Database using Python

## Overview
Focused on using SQL within Python to extract basic sales information (total quantity sold and total revenue) from a small SQLite database, displaying the results with print statements, and visualizing them with a bar chart.

## Objective
- Create a small SQLite database (`sales_data.db`) with a `sales` table.
- Use SQL to calculate total quantity sold and revenue per product.
- Display the results using print statements and a Matplotlib bar chart.
- Save the bar chart as `sales_chart.png`.

## Files
- `Task7_SalesSummary.ipynb`: Jupyter Notebook containing the Python script, SQL queries, printed results, and bar chart.
- `sales_data.db`: SQLite database file containing the synthetic `sales` table.
- `sales_chart.png`: Bar chart showing total revenue by product.

## Key Insights
- **Sales Summary**:
  - **Headphones**: 25 units sold, $1250.00 revenue.
  - **Laptop**: 8 units sold, $8000.00 revenue.
  - **Phone**: 17 units sold, $8500.00 revenue.
  - **Tablet**: 6 units sold, $1800.00 revenue.
- **Revenue Trends**: Phones generated the highest revenue ($8500.00), followed by Laptops ($8000.00). Headphones, despite having the highest quantity sold (25 units), had lower revenue due to their lower price ($50.00 per unit).

## How to Run
1. Install Python and the required libraries:
  - pip install pandas matplotlib jupyter
2. Launch Jupyter Notebook:
  - jupyter notebook
3. Open `Task7_SalesSummary.ipynb` and run all cells to reproduce the analysis.
4. View the bar chart (`sales_chart.png`) in the project directory.

## Tools Used
- Python (`sqlite3`, `pandas`, `matplotlib`)
- SQLite (built into Python)
- Dataset: Synthetic `sales` table created programmatically

## Date and Time of Submission
- Submitted on: 06:30 AM IST, Saturday, June 14, 2025.
