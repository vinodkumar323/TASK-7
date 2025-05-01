-> Basic Sales Summary using SQLite and Python:

This project demonstrates how to:
- Use SQLite database with Python
- Run basic SQL queries from Python
- Load SQL results into pandas
- Print summaries
- Visualize sales data with matplotlib

 ->Tools Used:
 
- Python (3.x)
- SQLite3 (built-in with Python)
- Pandas
- Matplotlib
- Jupyter Notebook

->Files Included:
 
-sales_data.db
-sales_summary.ipynb
-sales_chart.png 
->How to Run

1. Clone this repository or download the files.
2. Open the `sales_summary.ipynb` notebook in Jupyter.
3. Run all cells in order:
   - Creates or connects to `sales_data.db`
   - Runs SQL query to summarize sales
   - Loads data into a pandas DataFrame
   - Displays the summary
   - Plots revenue per product as a bar chart
->Sample Output:

Sales Summary:
Product	Total Qty	Revenue
Apple	15	18.0
Banana	35	17.5
Orange	18	14.4
Grapes	12	24.0
