# SQL-PROJECT-PERCENTATION-
This SQL-based project analyzes the Chinook digital music store database using MySQL. The goal is to extract business insights by performing advanced data queries on a relational schema containing 11 interconnected tables. Key entities include Customers, Employees, Invoices, Tracks, Albums, and Artists.

🔍 Project Overview
The project uses a variety of SQL concepts:

Joins (Inner, Left) to combine data from related tables.

Subqueries to extract nested results.

Window Functions like RANK() and SUM() OVER() to perform analytics without losing row-level detail.

Date functions to calculate employee experience using TIMESTAMPDIFF.

🧠 Key Insights & Queries
Track Duration: Found the average milliseconds played from the Track table.

Customer Metrics: Counted total customers and calculated revenue by customer using subqueries.

Revenue Analysis: Identified the top 5 countries generating the highest total invoice sales.

Sales Performance: Listed the top 5 customers by revenue and the top 3 artists by track count using joins and grouping.

Employee Performance: Used window functions to identify which employees handled the least and most revenue, and who their customers were.

Product Analysis: Retrieved the top 10 largest tracks by file size using window ranking.

📊 Skills Applied
Data Modeling Understanding: Through EER diagrams and schema mapping.

SQL Mastery: Including filtering, aggregation, ordering, grouping, and nested logic.

Business Thinking: Applied SQL for actionable analytics such as revenue tracking and user behavior.

📁 Dataset
The dataset is based on the Chinook open-source database, widely used for learning relational database design and querying.
