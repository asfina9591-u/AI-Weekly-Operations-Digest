# AI Weekly Operations Digest

An AI/ML-oriented retail operations analytics project that analyzes weekly business performance across stores, sales channels, promotions, returns, and staffing.

The project uses Python and Pandas to clean and analyze operational datasets and generate business insights through summary tables and visualizations.

---

## 📌 Project Overview

Retail businesses generate large amounts of operational data from transactions, stores, returns, promotions, and employee staffing.

This project analyzes that data to answer important business questions such as:

- Which store is performing the best?
- Which store has the lowest performance?
- How is revenue changing week by week?
- Which sales channel generates more revenue?
- What is the impact of promotions?
- How efficiently are staff hours being utilized?
- What is the return activity?
- Are there data-quality issues in the datasets?

The final output is a weekly operations analysis containing KPIs, business insights, and visualizations.

---

## 🎯 Objectives

The main objectives of this project are:

1. Clean and validate retail operational datasets.
2. Identify duplicate and invalid records.
3. Calculate weekly business KPIs.
4. Analyze store-level performance.
5. Compare online and in-store sales.
6. Analyze promotion usage and revenue.
7. Analyze returns.
8. Evaluate staffing efficiency.
9. Generate meaningful business insights.
10. Visualize important trends using charts.

---

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
│   ├── weekly_metrics.csv
│   ├── verification_results.csv
│   └── ai_digest.txt
│
├── requirements.txt
├── README.md
└── src/

📊 Dataset Summary
Transactions: 8,436
Returns: 408
Staffing records: 1,965
Stores: 5
📈 Key Results
Overall Business Performance
Total Revenue: 458,347.86
Total Transactions: 8,436
Average Transaction Amount: 54.33
Total Return Amount: 11,143.17
Total Staff Hours: 13,726.7
🏆 Best Performing Store

Store S01

Total Revenue: 108,550.32
Total Transactions: 2,024
Revenue per Staff Hour: 41.10
Transactions per Staff Hour: 0.768
📉 Lowest Performing Store

Store S05

Total Revenue: 79,730.00
Total Transactions: 1,482
Revenue per Staff Hour: 28.92
Transactions per Staff Hour: 0.539
🛒 Channel Performance
In-store Revenue: 315,453.45
Online Revenue: 142,894.41

The in-store channel generated the larger share of total revenue.

🎟️ Promotion Analysis
Revenue without promotion: 445,923.01
Revenue with promotion: 12,424.85
Average Order Value without promotion: 53.69
Average Order Value with promotion: 95.58
👥 Staffing Analysis

Staffing efficiency was analyzed using:

Total staff hours
Shift count
Employee count
Average hours per shift
Revenue per staff hour
Transactions per staff hour
🔍 Data Quality

The project identified:

140 duplicate transaction IDs
35 invalid transaction store records
15 invalid staffing store records
0 invalid return store records
📊 Visualizations

The project includes charts for:

Weekly revenue trends
Weekly transaction trends
Store performance
Channel performance
Promotion analysis
Staffing efficiency
Return trends
💡 Key Business Insights
S01 was the best-performing store.
S05 was the lowest-performing store.
In-store sales generated more revenue than online sales.
Promotional transactions had a higher average order value.
Staffing efficiency differed between stores.
Data-quality issues were identified and analyzed.
🚀 How to Run

Install the required libraries:

pip install -r requirements.txt

Open the Jupyter Notebook:

notebooks/weekly_operations_digest.ipynb

Run the notebook cells to reproduce the analysis.

👩‍💻 Author

Asfina Magi

B.Tech Computer Science & Engineering – AI/ML
