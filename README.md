# 📊 Banking Risk Analytics Dashboard

## 🧩 Project Overview

This project focuses on building a comprehensive **risk analytics dashboard** for the banking sector using **Power BI**. The goal is to assist banks in minimizing financial risk by identifying customers who are more likely to default on loans and making data-driven decisions around lending.

---

## 🎯 Problem Statement

Banks often face challenges in assessing credit risk accurately. The objective of this project is to analyze customer data to:

* Understand financial behavior and patterns
* Evaluate risk factors
* Support the loan approval process with data-backed insights

---

## 💡 Solution

We have developed an interactive and visually intuitive **Power BI dashboard** that consolidates various aspects of a customer's financial profile, such as:

* Estimated income
* Credit card balance
* Loan and deposit behavior
* Account types and usage patterns

Using these insights, banks can classify applicants based on their **likelihood to repay** and make informed decisions that reduce the risk of financial losses.

---

## 🗂️ Dataset Description

The data used in this project is composed of multiple interlinked tables, simulating a real-world banking environment. These tables are connected using **primary and foreign keys**, and include:

| Table Name             | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| `Client-Banking`       | Main table with client demographic and financial information       |
| `Banking Relationship` | Details of the customer’s interaction and engagement with the bank |
| `Gender`               | Gender mapping table using ID reference                            |
| `Investment Advisor`   | Advisor assignments and related client details                     |
| `Period`               | Time-based data like account opening dates                         |

---

## 📊 Dashboard Features

* Customer segmentation based on income bands
* Visualization of deposits, loans, and fees
* Heatmaps showing correlation among financial metrics
* Trend and relationship graphs (e.g., loans vs. credit card balance)
* Filters for nationality, occupation, risk class, and more

![image](https://github.com/user-attachments/assets/827c923d-d437-400c-b437-c0fc0b569fed)

**Loan Analysis Dashboard**
    
![image](https://github.com/user-attachments/assets/6dfe2e78-1cef-4e8f-b153-9864714b9d14)

**Deposit Analysis Dashboard**



---

## 🛠️ Tools & Technologies

* **Power BI** for dashboard creation and visualization
* **Python (Pandas, Seaborn, Matplotlib)** for exploratory data analysis
* **MySQL** for data storage and extraction (optional)
* **CSV file** as an alternate data source

---

## 🚀 Getting Started

### Requirements

* Python 3.x (optional for EDA)
* Power BI Desktop
* MySQL (only if using the database version)

### Steps

1. Clone the repository or download the files.
2. Open the Power BI file (`Banking_Dashboard.pbix`) to explore the dashboard.
3. (Optional) Run `eda_script.py` for Python-based data profiling.
4. (Optional) Set up MySQL and import the schema if using database version.

---

## 📌 Future Enhancements

* Incorporate machine learning models for predictive risk scoring
* Add time-series loan repayment trends
* Deploy the dashboard via Power BI Service with role-level access

---

## 🙌 Acknowledgements

This project is built for educational and analytical purposes, reflecting real-world use cases in the banking and financial services domain
