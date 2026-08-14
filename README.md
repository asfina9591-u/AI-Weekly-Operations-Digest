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
