# 📊 Task 7: Basic Sales Summary using SQLite and Python

## 🎯 Objective
This project demonstrates how to extract and visualize basic sales data from a SQLite database using Python. It includes querying, summarizing, and plotting data such as total quantity sold and total revenue per product.

---

## 🧰 Tools Used
- Python (Jupyter Notebook)
- SQLite (`sqlite3`)
- Pandas
- Matplotlib

---

## 🔄 Workflow
1. **Connect to Database**: `sales_data.db` is accessed using `sqlite3`.
2. **Run SQL Query**:
   ```sql
   SELECT product, SUM(quantity) AS total_qty, SUM(quantity * price) AS revenue
   FROM sales
   GROUP BY product
3.  Load into DataFrame: Query result is stored in a Pandas DataFrame.

4. Print Summary: The DataFrame is printed to display product-wise totals.

5. Plot Chart: A bar chart is created to visualize revenue by product.

6. Save Chart: Final chart is saved as sales_chart.png.

✅ Output
📄 Printed summary of total quantity and revenue per product

📊 Bar chart comparing revenue of each product

💾 Saved chart image (sales_chart.png)

📚 Learning Outcomes
SQL querying within Python

Data loading and summary with Pandas

Basic visualization with Matplotlib

Integration of database and Python for data reporting

