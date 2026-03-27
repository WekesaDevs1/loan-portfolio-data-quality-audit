# Loan Portfolio Data Quality Audit 🏦

A Python tool that automatically audits bank loan data,
detects quality issues, and generates a data quality score.

## 🔍 What It Does
- Detects missing values across all columns
- Flags duplicate loan IDs
- Identifies wrong data types in numeric columns
- Catches outlier loan amounts using standard deviation
- Finds inconsistent status values and branch name mismatches
- Outputs an overall Data Quality Score (%)

## 📊 Dataset
Synthetic Kenyan bank loan portfolio data — 32 rows simulating
real branch data with deliberately introduced quality issues.

## 🛠️ Tools Used
- Python
- Pandas
- NumPy

## 📁 Files
| File | Description |
|------|-------------|
| `loan_portfolio_audit.py` | Main audit script |
| `loan_transactions.csv` | Synthetic loan dataset |

## 🚀 How to Run
1. Clone this repository
2. Make sure you have Python, Pandas and NumPy installed
3. Run the script:
```
python loan_portfolio_audit.py
```

## 📈 Sample Output
```
========================================
       LOAN PORTFOLIO QUALITY REPORT
========================================
Total Rows Analysed  : 32
Missing Values       : 8
Duplicate IDs        : 2
Wrong Data Types     : 3
Outliers Detected    : 0
Status Casing Issues : 4
Branch Name Issues   : 1
----------------------------------------
DATA QUALITY SCORE   : 43.8%
Status: ❌ POOR — Major Cleaning Required
========================================
```

## 👤 Author
**Marvin Wekesa** — Senior Data Analyst
[LinkedIn](https://www.linkedin.com/in/marvin-wekesa-9754b0124)
```

