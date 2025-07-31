# 🧹 Superstore Sales Data Cleaning & Preprocessing

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow.svg)
![Status](https://img.shields.io/badge/Status-Dashboard%20Ready-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

> This project performs data cleaning and transformation on the **Superstore Sales dataset** to make it ready for interactive dashboarding and analytics.

---

## 📝 Project Description

The Superstore dataset, often used for sales analytics, contains inconsistencies such as:
- Extra spaces in column names
- Missing postal codes
- Incorrect date formats
- Duplicate entries

This Python script processes the raw data into a clean, consistent, and analysis-ready format suitable for BI tools like Tableau or Power BI.

---

## 💡 Features

- ✅ Standardized column names (snake_case)
- 🗓️ Converted date columns into datetime format
- 🧱 Filled missing postal codes
- 🧹 Removed duplicate records
- 📆 Created a new `month_year` column for time-based analysis
- 💾 Exported final cleaned dataset for visualization

---

## 🛠️ Skills & Tools Used

| Language | Libraries       | Concepts Applied                    |
|----------|------------------|-------------------------------------|
| Python   | `pandas`         | Data Cleaning & Preprocessing       |
|          | `datetime`       | Time Series Handling                |
|          |                  | Missing Value Imputation            |
|          |                  | Feature Engineering (`month_year`) |

---

## 📁 File Structure

```plaintext
📦 Superstore-Sales-Cleaning
├── superstore_sales_dataset.csv          # Raw dataset (input)
├── superstore_sales_cleaned_final.csv    # Cleaned, dashboard-ready output
├── clean_superstore.py                   # Python script for cleaning
└── README.md                             # Project documentation
