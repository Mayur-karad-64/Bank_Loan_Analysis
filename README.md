# Bank_Loan_Analysis
An end-to-end banking data analytics project. Features a SQL-based database setup, Python (Pandas/Seaborn) for Exploratory Data Analysis, and an interactive Power BI dashboard to visualize customer loans, deposits, and financial health

# 📊 Bank Loan Analysis Dashboard

This project focuses on analyzing banking customer data to understand **loan distribution, deposit behavior, and financial risk indicators**.
The project demonstrates an end-to-end **data analytics pipeline**, starting from data processing using **Python**, storing and managing data in **MySQL**, and creating an interactive dashboard using **Power BI**.

---

## 🎯 Project Objective

Banks handle large volumes of customer financial data. Analyzing this data helps financial institutions:

* Understand customer loan behavior
* Monitor deposit patterns
* Identify high-risk customers
* Analyze income distribution and customer demographics

This dashboard helps financial analysts gain insights into **loan performance, deposits, and customer risk profiles**.

---

## 🛠 Technologies Used

* **Python** – Data cleaning and preprocessing
* **Pandas & NumPy** – Data manipulation and analysis
* **MySQL** – Database storage and querying
* **Power BI** – Data visualization and dashboard creation
* **DAX** – Calculated measures and KPIs
* **Jupyter Notebook** – Data processing workflow

---

## 🔄 Project Workflow

Dataset
⬇
Data Cleaning & Transformation using **Python (Jupyter Notebook)**
⬇
Data Storage in **MySQL Database**
⬇
Data Connection with **Power BI**
⬇
Interactive **Banking Analytics Dashboard**

---

## 📊 Dashboard Features

The Power BI dashboard contains multiple analysis pages:

### 1️⃣ Summary Dashboard

* Total Clients
* Total Loan Amount
* Total Deposits
* Average Risk Weight
* Average Bank Loans
* Estimated Income

### 2️⃣ Loan Analysis

* Bank Loan by Banking Relationship
* Loan Distribution by Occupation
* Loan Distribution by Income Band
* Loan Distribution by Nationality

### 3️⃣ Deposit Analysis

* Total Deposit Overview
* Deposit Distribution by Occupation
* Deposit by Income Band
* Deposit by Nationality

---

## 📈 Key Insights

* **Total Clients:** 3000
* **Total Loan Amount:** 4.38 Billion
* **Total Deposit Amount:** 3.77 Billion
* **Business Lending:** 2.60 Billion
* **Average Risk Weight:** 2.25

These insights help understand the **financial distribution of loans and deposits across customer segments**.

---

## 🖼 Dashboard Preview

### Home Dashboard

![Home Dashboard](images/dashboard_home.png)

### Loan Analysis

![Loan Analysis](images/loan_analysis.png)

### Deposit Analysis

![Deposit Analysis](images/deposit_analysis.png)

### Summary Page

![Summary](images/summary_page.png)

---

## 📂 Repository Structure

```
Bank_Loan_Analysis
│
├── images
│   ├── dashboard_home.png
│   ├── loan_analysis.png
│   ├── deposit_analysis.png
│   └── summary_page.png
│
├── Banking.ipynb
├── banking_case_database_sql.sql
├── Banking Analysis.pbix
├── Banking_Analysis_Dashboard.pdf
└── README.md
```

---

## 🚀 How to Run the Project

1. Download the dataset and open the **Jupyter Notebook** file.
2. Run the Python notebook to clean and prepare the data.
3. Import the processed data into **MySQL database**.
4. Connect **Power BI** to the MySQL database.
5. Open the `.pbix` file to explore the dashboard.

---

## 📌 Future Improvements

* Add machine learning model for **loan default prediction**
* Deploy dashboard using **Power BI Service**
* Create automated **ETL pipeline**
* Add real-time banking data integration

---

## 👨‍💻 Author

**Mayur Karad**

B.Tech CSE Student | Aspiring Data Analyst

📌 GitHub:
https://github.com/Mayur-karad-64

---

⭐ If you found this project useful, consider giving it a **star** on GitHub!

Database Setup: Run the banking_case_database_sql.sql script in your SQL environment to set up the schema.

Run Analysis: Open Banking.ipynb in Jupyter or VS Code. Update the database connection credentials to match your local setup.

View Dashboard: Open Banking Analysis.pbix in Power BI Desktop to interact with the visual reports.
