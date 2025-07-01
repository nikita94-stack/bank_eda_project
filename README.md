# 🏦 Bank EDA Pipeline

An end-to-end exploratory data analysis project on structured banking data. This pipeline includes **data cleaning**, **feature engineering**, and **SQL-driven analysis** using Python and SQLAlchemy.

---

## 📁 Project Structure
```text
bank_eda_project/
├── Bank_Customers.ipynb                                   # Main EDA: SQL + business questions
├── Data_Cleaning_Feature_Engineering.ipynb                # Cleaning + feature creation                                  
├── README.md                                              # Project overview (this file)
└── requirements.txt                                       # Optional dependencies
```

## 🚀 Pipeline Overview
🧹 1. Data Cleaning & 🛠 Feature Engineering  
Standardize names, emails, and phone numbers  
Engineer features like `loan_to_balance_ratio`  
Generate synthetic `cibil_score` and assign risk bands  

📊 2. Main EDA Notebook  
Analyze customer behavior and transaction trends  
25+ SQL queries answered using Python + SQLAlchemy  
Credit risk bands, loan summaries, and inactivity analysis

## 🔧 Tech Stack
- **Python**: pandas, matplotlib, seaborn
- **SQL**: MySQL-compatible queries
- **SQLAlchemy**: for database interaction through Python
- **Jupyter Notebooks**: for interactive analysis and storytelling

## 🧠 SQL Techniques Used
This project makes extensive use of SQL for banking analytics, including:

- ✅ **JOINs** (inner, left, and multi-table)
- ✅ **CTEs** (Common Table Expressions)
- ✅ **Nested Queries**
- ✅ **Window Functions**:
  - `ROW_NUMBER()` to rank customers within branches
  - `RANK()` for identifying top transactions or balances
- ✅ **Aggregate Functions**: `SUM()`, `AVG()`, `COUNT()`
- ✅ **CASE WHEN** logic for credit risk banding

## 📥 Getting Started

1.Clone the repository:
```bash
git clone https://github.com/nikita94-stack/bank_eda_project.git
cd bank_eda_project
```

2.(Optional) Install required packages:
```bash
pip install -r requirements.txt
```

3.Run the notebooks in order:
Data_Cleaning_Feature_Engineering.ipynb
Bank_Customers.ipynb


## 📬 Contact
Created by @nikita94-stack
For suggestions or issues, open an issue

