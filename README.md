# 📊 UNITED STATES Tobacco Use Analysis (BRFSS 1995–2010)

<img width="436" height="454" alt="Image" src="https://github.com/user-attachments/assets/b7e643cb-5f0d-4943-95cd-72a6876f5d0e" />
## Overview
This repository contains an analysis of U.S. tobacco use trends between **1995 and 2010**, based on data from the **Behavioral Risk Factor Surveillance System (BRFSS)**. The project explores national, regional, and state-level smoking patterns, identifies fastest and slowest declines, and provides actionable insights for public health policy.

---

## ✨ Executive Summary
Between 1995 and 2010:
- Daily smoking fell from **20.0% to 12.9%** (−7.1 pp, ~35% relative drop).
- Never-smokers rose from **52.1% to 57.1%**.
- The **South** had the highest daily-smoking rates; the **West** the lowest.
- **Highest prevalence states**: Kentucky, Guam, West Virginia (23–25%).
- **Lowest prevalence states**: Utah, Puerto Rico, Virgin Islands (6–9%).
- **Fastest declines**: Nevada, Arizona, Delaware (−0.66 to −0.69 pp/yr).
- **Slowest declines**: West Virginia, Oklahoma, Louisiana (−0.21 to −0.35 pp/yr).

---

## 📂 Deliverables
- `US_Project_cleaned_Data.xlsx` → Cleaned dataset with 840 state-year observations.
- `Tobacco_Use_Analysis_Dashboard.xlsx` → Excel dashboard with pivot tables, regression formulas, and KPI charts.
- `Tobacco_Use_Interactive_Dashboard.html` → Interactive browser-based dashboard.

---

## 🔍 National Trend

| Year | Smoke Everyday | Smoke Some Days | Former Smoker | Never Smoked |
|------|----------------|-----------------|---------------|--------------|
| 1995 | 20.0%          | 2.7%            | 25.2%         | 52.1%        |
| 2000 | 17.6%          | 5.1%            | 24.4%         | 52.9%        |
| 2005 | 15.2%          | 5.4%            | 24.5%         | 54.9%        |
| 2010 | 12.9%          | 4.9%            | 25.1%         | 57.1%        |
| Change 1995–2010 | −7.1 pp | +2.2 pp | −0.1 pp | +5.0 pp |

![National Smoking Trends](images/national_trend.png)  
*Figure 1: National average smoking status, 1995–2010*  

![Smoking Status Composition](images/status_composition.png)  
*Figure 2: Composition of smoking status, 1995 vs. 2010*

---

## 🌎 Regional Comparison
- South consistently above national average.
- West consistently below national average.
- Gap narrowed only slightly over time.

![Regional Smoking Trends](images/regional_trend.png)  
*Figure 3: Daily smoking rate by U.S. Census region, 1995–2010*

---

## 🏛️ State-Level Rankings

### Highest Average Daily-Smoking Rates (1995–2010)

| State        | Region   | Avg. Smoke Everyday | Trend Slope (pp/yr) |
|--------------|----------|---------------------|---------------------|
| Kentucky     | South    | 24.9%               | −0.45               |
| Guam         | Territory| 24.4%               | −0.65               |
| West Virginia| South    | 22.8%               | −0.21               |
| Tennessee    | South    | 20.9%               | −0.41               |
| Missouri     | Midwest  | 20.8%               | −0.46               |
| Indiana      | Midwest  | 20.8%               | −0.50               |
| Oklahoma     | South    | 20.2%               | −0.22               |
| Ohio         | Midwest  | 20.2%               | −0.62               |
| Arkansas     | South    | 20.0%               | −0.46               |
| Nevada       | West     | 19.8%               | −0.69               |

### Lowest Average Daily-Smoking Rates (1995–2010)

| State          | Region     | Avg. Smoke Everyday |
|----------------|------------|---------------------|
| Virgin Islands | Territory  | 6.1%                |
| Puerto Rico    | Territory  | 8.4%                |
| Utah           | West       | 8.6%                |
| California     | West       | 10.8%               |
| D.C.           | South      | 12.2%               |
| New Jersey     | Northeast  | 13.6%               |
| Connecticut    | Northeast  | 14.1%               |
| Hawaii         | West       | 14.2%               |

![State Rankings](images/state_ranking.png)  
*Figure 4: States with highest and lowest average daily-smoking rates*

---

## 📉 Regression Trend Analysis

### Fastest Declining States (pp/yr)

| State      | Region   | Slope |
|------------|----------|-------|
| Nevada     | West     | −0.69 |
| Arizona    | West     | −0.66 |
| Delaware   | South    | −0.66 |
| Guam       | Territory| −0.65 |
| Rhode Island| Northeast| −0.62 |
| Ohio       | Midwest  | −0.62 |
| Maine      | Northeast| −0.59 |
| New York   | Northeast| −0.58 |

### Slowest Declining States (pp/yr)

| State      | Region   | Slope |
|------------|----------|-------|
| D.C.       | South    | −0.36 |
| Louisiana  | South    | −0.35 |
| Utah       | West     | −0.34 |
| Minnesota  | Midwest  | −0.33 |
| Wyoming    | West     | −0.32 |
| Alabama    | South    | −0.26 |
| Oklahoma   | South    | −0.22 |
| West Virginia| South  | −0.21 |

![Regression Slopes](images/regression_slopes.png)  
*Figure 5: Regression slopes — fastest vs. slowest declines*

---

## 🚀 Actionable Insights
- Prioritize **cessation funding in the South** (Kentucky, West Virginia, Tennessee).
- Replicate strategies from **fastest-declining states** (Nevada, Arizona, Delaware, Ohio).
- Address the **rise in occasional smoking** (“some days” category grew from 2.7% → 4.9%).
- Focus on **high-prevalence + slow-decline states** (West Virginia, Oklahoma).

---

## 🛠️ Tech Stack
- **Excel**: Pivot tables, regression formulas, KPI dashboards.
- **Python (NumPy)**: Regression validation.
- **HTML/CSS/JS**: Interactive dashboard.

---

## 📜 License
This project is for **educational and research purposes**. Data sourced from the **CDC BRFSS survey**.
