# 🤖 AI Weekly Operations Digest

## 📌 Project Overview

AI Weekly Operations Digest is a retail data analytics project that analyzes weekly business performance using transaction, store, staffing, returns, and promotion data.

The project focuses on data cleaning, KPI analysis, store performance, sales channels, promotions, returns, staffing efficiency, and business insights.

## 🎯 Objectives

- Clean and validate retail datasets
- Analyze weekly revenue and transactions
- Compare store performance
- Analyze online vs in-store sales
- Analyze promotion performance
- Analyze returns
- Measure staffing efficiency
- Generate business insights using KPIs and visualizations

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure

```text
AI-Weekly-Operations-Digest/
│
├── data/
│   ├── transactions.csv
│   ├── returns.csv
│   ├── staffing_shifts.csv
│   ├── stores.csv
│   │
│   └── cleaned/
│       ├── transactions_cleaned.csv
│       ├── returns_cleaned.csv
│       ├── staffing_cleaned.csv
│       └── stores_cleaned.csv
│
├── notebooks/
│   └── weekly_operations_digest.ipynb
│
├── outputs/
│
├── requirements.txt
└── README.md
```

## 📊 Dataset Summary

| Dataset | Records |
|---|---:|
| Transactions | 8,436 |
| Returns | 408 |
| Staffing Records | 1,965 |
| Stores | 5 |

## 📈 Key Results

### Overall Business Performance

- **Total Revenue:** 458,347.86
- **Total Transactions:** 8,436
- **Average Transaction Amount:** 54.33
- **Total Return Amount:** 11,143.17
- **Total Staff Hours:** 13,726.7

### 🏆 Best Performing Store

**Store S01**

- **Total Revenue:** 108,550.32
- **Total Transactions:** 2,024
- **Revenue per Staff Hour:** 41.10
- **Transactions per Staff Hour:** 0.768

### 📉 Lowest Performing Store

**Store S05**

- **Total Revenue:** 79,730.00
- **Total Transactions:** 1,482
- **Revenue per Staff Hour:** 28.92
- **Transactions per Staff Hour:** 0.539

## 🛒 Channel Performance

| Channel | Revenue |
|---|---:|
| In-store | 315,453.45 |
| Online | 142,894.41 |

The **in-store channel generated the larger share of total revenue**.

## 🎟️ Promotion Analysis

| Promotion | Revenue | Transactions | Average Order Value |
|---|---:|---:|---:|
| No Promotion | 445,923.01 | 8,306 | 53.69 |
| Promotion Used | 12,424.85 | 130 | 95.58 |

Promotional transactions had a higher average order value in the analyzed data.

## 👥 Staffing Analysis

Staffing efficiency was analyzed using:

- Total staff hours
- Shift count
- Employee count
- Average hours per shift
- Revenue per staff hour
- Transactions per staff hour

## 🔍 Data Quality

The project identified:

- **140** duplicate transaction IDs
- **35** invalid transaction store records
- **15** invalid staffing store records
- **0** invalid return store records

## 📊 Visualizations

The project includes charts for:

- Weekly revenue trends
- Weekly transaction trends
- Store performance
- Channel performance
- Promotion analysis
- Staffing efficiency
- Return trends

## 💡 Key Business Insights

1. **S01** was the best-performing store.
2. **S05** was the lowest-performing store.
3. **In-store sales** generated more revenue than online sales.
4. **Promotional transactions** had a higher average order value.
5. Staffing efficiency differed across stores.
6. Data-quality issues were identified and analyzed.

## 🚀 How to Run

### Install the required libraries

```bash
pip install -r requirements.txt
