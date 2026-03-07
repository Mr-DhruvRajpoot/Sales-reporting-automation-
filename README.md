# ⚙️ Reporting Automation & Data Operations — Sales Pipeline
### Replacing 4+ Hours of Manual Excel Work With a Single Script

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://python.org)
[![pandas](https://img.shields.io/badge/pandas-Pipeline-green)](https://pandas.pydata.org)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen)]()

---

## 📌 Project Overview

Analysts typically spend **60–80% of their time cleaning and preparing data** rather than analysing it. This project builds a **reusable automated data pipeline** that handles messy real-world sales data — automatically detecting quality issues, treating missing values, flagging anomalies, and generating a standardised monthly report.

**Time saved per reporting cycle:**

| Task | Manual | Automated |
|---|---|---|
| Data quality check | 45 min | 2 seconds |
| Missing value treatment | 60 min | 2 seconds |
| Anomaly detection | 90 min | 2 seconds |
| Summary report | 60 min | 2 seconds |
| **Total** | **~4.5 hours** | **< 10 seconds** |

---

## 🔍 Key Features

- **Automated Data Quality Report** — missing values, data types, duplicates flagged instantly
- **Intelligent Imputation** — median for numerical, mode for categorical, with treatment log
- **Anomaly Detection** — IQR-based outlier identification on revenue columns
- **Auto-Generated Summary Report** — regional breakdown, best/worst months, totals
- **Trend Visualisation** — month-over-month revenue automatically plotted
- **Fully Scalable** — handles any number of regions, products, or time periods without code changes

---

## 📊 Pipeline Architecture

```
Raw CSV (messy)
    ↓
Data Quality Report  →  flags missing values, types, duplicates
    ↓
Cleaning Pipeline    →  intelligent imputation with treatment log
    ↓
Anomaly Detection    →  IQR method, flags outliers
    ↓
Summary Report       →  auto-generated executive summary
    ↓
Trend Visualisation  →  month-over-month charts
```

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Language | Python 3.10 |
| Data Manipulation | pandas, NumPy |
| Visualization | matplotlib, seaborn |
| Environment | Jupyter Notebook |

---

## 📁 Project Structure

```
sales-reporting-automation/
├── Project5_Reporting_Automation.ipynb
├── Stores_Sales_with_mising_values.csv
├── Stores_Sales_with_dates.csv
└── README.md
```

---

## ▶️ How to Run

```bash
git clone https://github.com/Mr-DhruvRajpoot/sales-reporting-automation.git
cd sales-reporting-automation
jupyter notebook Project5_Reporting_Automation.ipynb
```

---

## 👤 Author

**Dhruv Rajpoot** — Data Analyst | Python · SQL · Tableau | Delhi, India
Open to remote opportunities globally.

🔗 [GitHub Portfolio](https://github.com/Mr-DhruvRajpoot)
