# Sales-Trend-Analysis
Aasimtask6

1.Task Objective
Analyze online sales trends over time using SQL aggregations. The focus is on monthly revenue and order volume using SQLite functions.

2.Table Creation
A table named online_sales is created with fields: order_id, order_date, product_id, and amount.

3.Data Insertion
Ten sample sales records are inserted into the online_sales table, spanning from January to April 2024.

4.Monthly Aggregation
A view sales_monthly is created using strftime() to extract year and month from order_date. Monthly revenue and distinct order volume are calculated using SUM() and COUNT() respectively.

5.Data Retrieval
All records from the view are queried, with optional filtering (e.g., only for year 2024) to analyze specific time periods.

6.Insight Use
The monthly revenue and order volume trends help in understanding peak sales periods and performance consistency over time.
