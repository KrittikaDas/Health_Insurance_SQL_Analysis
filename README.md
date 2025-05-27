# 📊 Health Insurance SQL & Visualization Project

A data analysis and visualization project using the **Health Insurance Cross-Sell Prediction** dataset from Kaggle. This project explores customer behavior and policy conversion using **SQL queries** on SQLite and visualizations in **Google Colab**.

---

## 🧾 Dataset Description

- **Source**: [Kaggle - Health Insurance Cross-Sell Prediction](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction)
- **Context**: A car insurance company is trying to sell health insurance products to existing customers. The dataset includes customer demographics, vehicle details, and responses to health insurance offers.

---

## 📌 Objectives

- Understand customer conversion behavior
- Identify key customer segments based on age, gender, region, vehicle age, and premium
- Support business decisions with visual insights
- Prepare data for Tableau/Power BI dashboards

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `Health_Insurance_SQL_Analysis.ipynb` | Main Colab notebook with SQL queries and charts |
| `health_insurance_cleaned.csv` | Flattened dataset exported for Tableau/Power BI use |
| `README.md` | Project overview and details |

---

## 🧠 Key Analyses

- ✅ Conversion Rate by Gender
- ✅ Conversion by Vehicle Age
- ✅ Average Premium by Age Group
- ✅ Region-wise interest in health policies
- ✅ Driving License ownership vs. conversion
- ✅ Most effective Sales Channels

---

## 🔍 SQL Used

SQLite via Python's `sqlite3` module is used to simulate a relational database with:
- `customers` table
- `vehicles` table
- `policies` table

Joins and aggregation queries help extract insights from the data.

---

## 📊 Visualizations

Created using `matplotlib`:
- Bar charts: Conversion by vehicle age, region
- Pie chart: Conversion by gender
- Line/bar plots: Premium by age group
- Exported flat CSV for interactive BI tools

---

## 🚀 Tools Used

- Google Colab (Python Notebook)
- SQLite (via `sqlite3`)
- Pandas
- Matplotlib
- Tableau (optional export)

---

## 📈 How to Run

1. Open the Colab notebook in Google Colab
2. Upload `train.csv` from Kaggle
3. Run cells step-by-step
4. View plots and export cleaned CSV for dashboards

---

## 👨‍💻 Author

**Krittika Das**  
Data Analyst | Python | SQL | Tableau 

---
