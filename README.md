# Bank_Loan_Analysis
An end-to-end banking data analytics project. Features a SQL-based database setup, Python (Pandas/Seaborn) for Exploratory Data Analysis, and an interactive Power BI dashboard to visualize customer loans, deposits, and financial health

Here is a professionally formatted README.md file ready for copy-pasting.

Important Note: Before you upload your .ipynb file, make sure to change your SQL password line to something like password="YOUR_PASSWORD" to keep your local environment secure.

Banking Customer Analysis & Financial Dashboard 🏦
An end-to-end data analytics project that explores banking customer demographics, loan distributions, and deposit trends. This project transitions from raw database management in SQL to exploratory analysis in Python, concluding with an executive-level Power BI dashboard.

📌 Project Overview
The objective of this project is to analyze a dataset of 3,000 banking clients to identify high-value customer segments and evaluate the bank's current loan-to-deposit health.

Key Metrics Visualized:
Total Loan Portfolio: $4.38bn

Total Deposits: $3.77bn

Business Lending: $2.60bn

Customer Base: 3,000 active clients across various income bands.

🛠️ Tools & Technologies
Database: MySQL (Data storage and retrieval)

Programming: Python 3.x

Libraries: Pandas, Matplotlib, Seaborn, MySQL-Connector

Visualization: Power BI Desktop

📂 Project Structure
banking_case_database_sql.sql: SQL scripts for database initialization and table queries.

Banking.ipynb: Jupyter Notebook containing data cleaning, statistical profiling, and correlation heatmaps.

Banking Analysis.pbix: The Power BI file containing the interactive dashboard.

Dashboard_Preview.pdf: Screenshots of the multi-page dashboard (Loan Analysis, Deposit Analysis, and Summary).

📊 Analysis Insights
1. Data Processing (SQL & Python)
Connected to a MySQL instance to pull customer records.

Conducted statistical analysis on income bands (High, Mid, Low) and credit card balances.

Generated correlation heatmaps to visualize the relationship between Gender and Credit Card ownership.

2. Dashboard Highlights (Power BI)
Income Band Impact: Customers in the "High" income band account for 53.12% of all bank loans ($942.49M).

Product Performance: Business lending is the strongest performing asset at $2.60bn.

Geographic & Occupational Trends: Analysis of loan and deposit volumes broken down by nationality and job sector (Retail, Commercial, Institutional, Private Banking).

🚀 How to Use
Database Setup: Run the banking_case_database_sql.sql script in your SQL environment to set up the schema.

Run Analysis: Open Banking.ipynb in Jupyter or VS Code. Update the database connection credentials to match your local setup.

View Dashboard: Open Banking Analysis.pbix in Power BI Desktop to interact with the visual reports.
