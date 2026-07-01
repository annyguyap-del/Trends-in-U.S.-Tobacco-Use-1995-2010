# 📊 Tobacco Use Analysis (BRFSS 1995–2010)

## Overview
This repository contains an analysis of U.S. tobacco use trends between **1995 and 2010**, based on data from the **Behavioral Risk Factor Surveillance System (BRFSS)**. The project explores national, regional, and state-level smoking patterns, identifies fastest and slowest declines, and provides actionable insights for public health policy.

## ✨ Key Findings
- Daily smoking declined from **20.0% (1995)** to **12.9% (2010)** — a **35% relative drop**.
- The **South** consistently reported the highest daily-smoking rates; the **West** the lowest.
- The share of **never-smokers increased** from **52.1% to 57.1%**.
- **Highest prevalence states**: Kentucky, Guam, West Virginia (23–25%).
- **Lowest prevalence states**: Utah, Puerto Rico, Virgin Islands (6–9%).
- **Fastest declines**: Nevada, Arizona, Delaware (−0.66 to −0.69 pp/yr).
- **Slowest declines**: West Virginia, Oklahoma, Louisiana (−0.21 to −0.35 pp/yr).

## 📂 Deliverables
- `US_Project_cleaned_Data.xlsx` → Cleaned dataset with 840 state-year observations.
- `Tobacco_Use_Analysis_Dashboard.xlsx` → Excel dashboard with pivot tables, regression formulas, and KPI charts.
- `Tobacco_Use_Interactive_Dashboard.html` → Interactive browser-based dashboard.

## 🔍 Methodology
- **Data Cleaning**: Removed duplicates, validated percentages, added Census region classification.
- **Exploratory Analysis**: Pivot tables for national, regional, and state-level trends.
- **Regression Analysis**: Linear slope of daily smoking vs. year, computed with Excel’s `SLOPE()` and cross-validated in Python (`NumPy polyfit`).
- **Interpretation**: Compared decline rates, highlighted policy implications, and flagged rise in “some days” smoking.

## 🚀 Actionable Insights
- Prioritize **cessation funding in the South** (Kentucky, West Virginia, Tennessee).
- Study and replicate **fastest-declining states** (Nevada, Arizona, Delaware, Ohio).
- Address the **rise in occasional smoking** — falling daily rates don’t mean overall smoking is disappearing.
- Focus on **high-prevalence + slow-decline states** (West Virginia, Oklahoma) for maximum impact.

## 🛠️ Tech Stack
- **Excel**: Pivot tables, regression formulas, KPI dashboards.
- **Python (NumPy)**: Regression validation.
- **HTML/CSS/JS**: Interactive dashboard.

## 📈 Visuals
- National smoking trends (1995–2010).
- Regional comparisons (South vs. West).
- State-level rankings (highest vs. lowest).
- Regression slopes (fastest vs. slowest declines).

## 📜 License
This project is for **educational and research purposes**. Data sourced from the **CDC BRFSS survey**.

