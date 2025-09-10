# Task-06-Basic-Sales-AnalysisPerfect 👍 Here’s a ready-to-use README.md for your Task 06 GitHub submission:

Task 06 - Get Basic Sales Summary from a Tiny SQLite Database using Python

📌 Objective

The goal of this task is to connect Python with a small SQLite database, extract simple sales information (like total quantity sold and revenue by product), and visualize the results using a bar chart.

🛠 Tools & Libraries Used

Python

SQLite3 (built-in with Python)

Pandas (for data handling)

Matplotlib (for chart visualization)

🚀 Steps Performed

1. Created/Loaded Database

Database file: sales_data.db

Table: sales (product, quantity, price)

Inserted a few rows of sample sales data.

2. Connected Python to SQLite

Used sqlite3.connect("sales_data.db").

3. Wrote SQL Query

SELECT product, 
       SUM(quantity) AS total_qty, 
       SUM(quantity * price) AS revenue
FROM sales
GROUP BY product;

4. Loaded Data into Pandas

Used pd.read_sql_query() to fetch query results.

5. Displayed Output

Printed a summary table.

6. Visualized Data

Created a bar chart showing Revenue by Product.

Saved chart as sales_chart.png.


📊 Example Output

Summary Table:

product	total_qty	revenue

Apple	15	75.0
Banana	30	60.0
Orange	15	45.0


Bar Chart (Revenue by Product):
📂 Saved as sales_chart.png


📁 Files in Repository

task6.py → Python script

task6.ipynb → Jupyter Notebook version (optional)

sales_data.db → SQLite database file

sales_chart.png → Bar chart image

README.md → Explanation of the task

✅ Task Completed Successfully!


---

Would you like me to also make this README shorter (4–5 lines) so you can quickly paste it if your internship portal doesn’t require too much detail?
