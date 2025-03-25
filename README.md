# Bike-Store-w-SQLite
The notebook is aimed at analyzing sales and inventory data for a bike store using an SQLite database. 

Steps Performed in the Notebook:

1.Importing Necessary Libraries:
- numpy, pandas: Data handling and manipulation.
- sqlite3: Connecting and interacting with the SQLite database.
- matplotlib, seaborn: Data visualization.

Loading and Preparing Data:
- Reading multiple CSV files: stocks.csv, stores.csv, staffs.csv, products.csv, orders.csv, order_items.csv, customers.csv, categories.csv, and brands.csv.
- Loading these CSV files into corresponding tables in the SQLite database using to_sql().

Database Connection & Setup:
- Establishing a connection to the SQLite database (bike_store.db).
- Setting up connection parameters for analysis.

Exploratory Data Analysis (EDA):
- Descriptive Statistics: Viewing data samples from various tables (stocks, stores, staffs, etc.).
- Checking data types and handling missing values where applicable.

Data Aggregation & Analysis:
- Using SQL queries to join multiple tables and extract relevant data for analysis.
- Performing grouped operations to summarize sales by:
    - Products.
    - Stores.
    - Customers.
- Creating pivot tables to show sales distribution.

Visualization:
- Generating bar charts, pie charts, and other visualizations to show sales performance and inventory distribution.

Analyzing Sales Performance:
- Finding top-performing products, stores, and customer demographics.
- Analyzing product categories and their sales distribution.

Analyzing Inventory:
- Reviewing inventory levels across different stores.
- Identifying stock shortages and high-performing products.

Conclusions & Insights :
- The notebook  aims to identify trends and improve inventory management.
- Focus on improving sales by analyzing customer preferences and sales distribution.
