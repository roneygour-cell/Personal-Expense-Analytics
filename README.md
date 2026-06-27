<h1 align="center">💰 Personal Expense Analytics</h1>
<h3 align="center">CODTECH IT Solutions — Data Analytics Internship | Task 1</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-9cf?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
</p>

---

## 👤 Intern Information

| Field | Details |
|---|---|
| **Intern Name** | Yogesh Kumar Gour |
| **Intern ID** | CITS2677 |
| **Company** | CODTECH IT Solutions Pvt. Ltd |
| **Domain** | Data Analytics |
| **Task** | Personal Expense Analytics |
| **Mentor** | Neela Santhosh Kumar |
| **Duration** | 4 Weeks |

---

## 📌 Objective

Perform an end-to-end exploratory data analysis on a personal expense dataset to uncover spending patterns, category-wise breakdowns, monthly trends, payment mode preferences, and derive actionable financial insights using Python.

---

## 📁 Project Structure

```
Task-1_Personal_Expense_Analytics/
│
├── Personal_Expense_Analytics.ipynb   # Main Jupyter Notebook
├── personal_expenses.csv              # Expense dataset (144 records)
└── README.md                          # Project documentation
```

---

## 📊 Dataset Description

The dataset contains **144 expense records** spanning **January to December 2024**, with the following columns:

| Column | Description |
|---|---|
| `Date` | Date of the transaction |
| `Category` | Expense category (Food, Transport, Shopping, etc.) |
| `Description` | Brief description of the expense |
| `Amount` | Transaction amount in Indian Rupees (₹) |
| `Payment_Mode` | Mode of payment (UPI, Cash, Credit Card, Net Banking) |
| `Month` | Month name of the transaction |

### Categories Covered
`Food` · `Transport` · `Entertainment` · `Healthcare` · `Education` · `Utilities` · `Shopping` · `Personal Care`

---

## 🛠️ Technologies Used

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and aggregation |
| `numpy` | Numerical computations |
| `matplotlib` | Charts and plots |
| `seaborn` | Statistical visualizations and heatmaps |

---

## 📈 Analysis Performed

1. **Data Loading & Inspection** — Shape, data types, sample records
2. **Data Quality Check** — Null values, duplicates, unique categories
3. **Feature Engineering** — Month number, quarter, week extraction
4. **Overall Spending Summary** — Total spend, average transaction, min/max
5. **Category-Wise Analysis** — Total, average, and % share per category (Pie + Bar chart)
6. **Monthly Trend Analysis** — Month-over-month spending with trend line
7. **Payment Mode Analysis** — Donut chart + bar chart by transaction count and amount
8. **Category × Month Heatmap** — Spending matrix across all months and categories
9. **Quarterly Breakdown** — Q1 to Q4 comparison
10. **Top 10 Transactions** — Highest individual expenses
11. **Key Insights & Recommendations** — Data-driven financial takeaways

---

## 📌 Key Insights

- 🏆 **Food** is the highest spending category across the year
- 📅 **October** (festival season) and **December** (year-end) recorded peak expenditures
- 📱 **UPI** is the dominant payment method, reflecting digital payment adoption
- 📉 A dedicated savings plan for festival months and year-end could reduce overall spend by 15–20%
- 💡 Average monthly expenditure was consistent, with seasonal spikes in Q4

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/[your-github-username]/[repo-name].git

# 2. Navigate to Task 1 folder
cd Task-1_Personal_Expense_Analytics

# 3. Install dependencies
pip install pandas numpy matplotlib seaborn notebook

# 4. Launch Jupyter Notebook
jupyter notebook Personal_Expense_Analytics.ipynb
```

---

## 🏢 About the Internship

This project was completed as **Task 1** of the **CODTECH IT Solutions Data Analytics Virtual Internship**, as part of the mandatory internship curriculum requirement. The internship is a 4-week program covering key concepts in data analytics using Python.

---

<p align="center">
  <b>Made with ❤️ by Yogesh Kumar Gour | CODTECH IT Solutions Pvt. Ltd.</b>
</p>
