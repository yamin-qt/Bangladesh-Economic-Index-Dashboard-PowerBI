# 📊 Bangladesh Economic Index Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi)
![Data Source](https://img.shields.io/badge/Data-Kaggle-20BEFF?style=for-the-badge&logo=kaggle)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

A multi-page Power BI dashboard analyzing Bangladesh's economic and social indicators from **2013 to 2023**, built for a data visualization competition. The dashboard tracks how key indices — unemployment, cost of living, purchasing power, crime, and social stability — have shifted over a decade, giving decision-makers a snapshot of where Bangladesh stands and where it is heading.

---

## 📂 Dashboard Pages

| Page | Description |
|---|---|
| Bangladesh Economic Index | High-level country overview across all major indicators |
| Executive Summary | KPI cards with goal tracking for 2020 vs 2023 comparison |
| Economic & Social Life Indicators | Deep-dive correlations, trends, and breakdowns by year and age group |

---

## 📈 Key Metrics Tracked

- **Comfort of Life Index** — 101.00 (32.89% above target)
- **Cost of Living Index** — 26.60
- **Purchasing Power Index** — 26.90
- **Crime Index** — 62.60
- **Risk of Life Index** — 168.00
- **Youth Unemployment (15–24)** — 12.95%
- **Adult Unemployment (25+)** — 2.94%

---

## 🔍 How I Built This

1. **Data Source** — Sourced dataset from Kaggle covering Bangladesh economic indicators (2013–2023)
2. **Data Cleaning** — Handled missing values, standardized column formats, and validated year-wise consistency using Power Query
3. **Data Modeling** — Built relationships between indicator tables; created calculated measures using DAX for goal variance (% above/below target)
4. **Visualization Design** — Designed 3 report pages with a consistent color system: green for on-target, red for off-target
5. **Trend Analysis** — Used line charts and scatter plots to surface correlations (e.g., Unemployment vs Crime, Purchasing Power vs Cost of Living over time)

---

## 💡 Insights & Decision Value

- Youth unemployment (15–24) is **4x higher** than adult unemployment — signals a structural workforce gap, not a cyclical issue
- Crime index and safety index move in **opposite directions** over time — improving safety does not directly reduce crime rate
- Purchasing power and cost of living show **low correlation**, meaning income growth is not keeping pace with living costs
- Comfort of Life index exceeded its target by **+32.89%** — the strongest performing KPI across the board

---

## 🚀 Real-World Applications

This type of dashboard can be used by:
- **Government policy teams** — to allocate resources toward high-unemployment age groups
- **NGOs and development organizations** — to identify regions or demographics needing intervention
- **Investors and businesses** — to assess market risk and purchasing power before entering Bangladesh
- **Academic researchers** — as a baseline for socioeconomic studies

---

## ⚠️ Limitations & What Can Be Done Better

- Data is at **national level only** — a district or divisional breakdown would reveal regional disparities
- No **predictive modeling** — adding a forecasting layer (e.g., regression trendline to 2027) would increase decision value
- Kaggle dataset may have **gaps or estimation errors** compared to official BBS (Bangladesh Bureau of Statistics) sources
- Dashboard is **static** — connecting to a live API or annual data refresh would make it production-ready

---

## 📚 What I Learned

- Building **multi-page report navigation** in Power BI with consistent UX across pages
- Writing **DAX measures** for goal variance calculations and conditional formatting logic
- Designing visuals that tell a story — not just display numbers
- How to present **correlation analysis** (scatter plots, dual-axis line charts) in a business-readable format

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard design and DAX
- **Power Query** — Data cleaning and transformation
- **Kaggle** — Data source
- **Microsoft Excel** — Initial data exploration

---

## 📸 Dashboard Preview




https://github.com/user-attachments/assets/bd8b7dde-1dca-4472-bb3e-1087d82538ff


