# Northwind Traders Data Analysis Project
## Scenario

You are a Data Analyst at Northwind Traders, an international gourmet food distributor. Management relies on data-driven insights to make strategic decisions across multiple areas of the business. This project focuses on:

- ✅ Evaluating Employee Performance – Identifying key contributors to improve productivity.
- ✅ Understanding Product & Category Sales – Optimizing inventory and marketing strategies.
- ✅ Analyzing Sales Growth – Monitoring trends, tracking company progress, and forecasting demand.
- ✅ Evaluating Customer Purchase Behavior – Targeting high-value customers with promotional incentives.

Using PostgreSQL window functions, you will generate these essential insights, helping management drive better business decisions.



## Database Schema

To build efficient SQL queries, referencing the database schema is essential. The Northwind database contains over a dozen tables, but for this project, we focus only on the most relevant ones.

📌 Below is a modified schema diagram highlighting the necessary tables for analysis:

(If you're curious about the full schema, refer to the original [Northwind_schema](ER.png).



## Technologies Used

    PostgreSQL – Querying and analyzing structured data
    SQL Window Functions – Advanced analytics for ranking, cumulative sales, and trend tracking
    Jupyter Notebook – Running queries and visualizing data
    Python (psycopg2 & pandas) – Query execution and data manipulation

Key SQL Techniques Used

- 🟢 Window Functions (ROW_NUMBER(), RANK(), DENSE_RANK(), SUM() OVER(), AVG() OVER())
- 🟢 Common Table Expressions (CTEs) (WITH category_sales AS (...))
- 🟢 Aggregations & Joins (SUM(), COUNT(), JOIN)
- 🟢 Date Functions (DATE_TRUNC(), EXTRACT())
