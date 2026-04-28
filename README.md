# Pandas Advanced Project: Real-World Data Analysis

---

## 📌 Project Overview

A comprehensive end-to-end data analysis project built entirely with **Pandas** and Python. This notebook demonstrates mastery of advanced data manipulation, cleaning, aggregation, time series analysis, and multi-dimensional business reporting — all applied to a realistic e-commerce dataset.

---

## 🧩 Problem Solved

Raw business data is messy, fragmented, and hard to interpret. This project tackles the full data pipeline:

- **Dirty data** with missing values, duplicates, and inconsistent types → cleaned and transformed
- **Siloed datasets** (employees, departments, salaries) → merged into unified views
- **Raw transactional records** → aggregated into actionable KPIs by product, region, customer type, and time period
- **Unstructured time data** → converted into resampled trends and rolling averages for forecasting

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python 3.x** | Core language |
| **Pandas** | Data manipulation, groupby, merge, pivot, reshape |
| **NumPy** | Numerical operations and random data generation |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical plotting |
| **Jupyter Notebook** | Interactive development environment |

---

## 📊 Key Results

- Performed **multi-level GroupBy aggregation** across departments, regions, and customer segments — computing sum, mean, min, max simultaneously
- Built a **12-month e-commerce sales dataset** (365 days × 5 products × 4 regions) and extracted 6 distinct analyses from it
- Identified the **best-performing region per product** using pivot tables and iterative cross-analysis
- Computed **7-day and 30-day rolling averages** on daily sales, enabling trend smoothing and seasonality detection
- Executed **multi-key DataFrame merges** (inner, left, outer joins) across employee, department, and salary tables
- Reshaped data using `melt`, `stack/unstack`, and `crosstab` for both wide and long format reporting

---

## 💡 Technical Skills Demonstrated

**Data Wrangling**
- Handling missing values (`dropna`, `fillna` with mean/mode/forward-fill strategies)
- Removing duplicates and standardizing column types
- Boolean masking, `.loc`/`.iloc` indexing, and conditional filtering

**Aggregation & Grouping**
- `groupby()` with multi-column aggregation using `agg()`
- `filter()` on groups (e.g., departments where avg salary > threshold)
- `transform()` for within-group normalization

**Merging & Reshaping**
- `merge()` with `on`, `left_on/right_on`, and `how` parameters
- Chained multi-DataFrame joins
- `pd.concat()`, `pd.melt()`, `pivot_table()`, `crosstab()`

**Time Series**
- `pd.date_range()` and `DatetimeIndex` operations
- `resample()` for weekly, monthly, and quarterly aggregation
- Rolling windows and lag-based feature creation

**Advanced Pandas**
- Custom lambda functions in `apply()` and `filter()`
- Display configuration with `pd.set_option()`
- Synthetic dataset generation with reproducible `np.random.seed()`

---

## 💼 Business Impact

This project mirrors real data analyst workflows across industries:

- **E-commerce teams** can replicate the product × region pivot analysis to identify geographic revenue gaps
- **HR/Finance departments** can use the GroupBy + salary filtering logic for compensation benchmarking
- **Operations managers** benefit from the time series resampling approach to track KPIs weekly/monthly/quarterly
- **Data engineers** can use the multi-merge pipeline as a template for joining transactional systems (CRM, ERP, HRIS)

The techniques demonstrated — data cleaning, aggregation, reshaping, and time series analysis — collectively address **80% of real-world analytics tasks** in business settings.

---
## 🌐 <a href="https://69be6cadb8d2bc2e21ccfdfc--hilarious-pasca-037fff.netlify.app/">✨ Visit My Portfolio ✨</a>

---

<p align="center">
  🚀 <b>Turning Data into Insights | SQL | Analytics | Problem Solving</b>
</p>
