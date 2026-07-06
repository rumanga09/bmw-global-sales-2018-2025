# bmw-global-sales-2018-2025

# BMW Global Sales Analysis (2018–2025)

An end-to-end data analysis project exploring global BMW sales trends and the key drivers of electric vehicle (BEV) adoption — presented as the portfolio project for the **BNSP Data Analyst competency assessment** (July 2026, declared competent).

---

## 🔗 Quick Links

| Resource | Link |
|---|---|
| Dataset | https://www.kaggle.com/datasets/mohamedamiralkrdawy/bmw-global-sales-analysis-20182025|
| Interactive Dashboard (Looker Studio) | https://datastudio.google.com/reporting/ee6eb8d7-1672-4bb3-87b3-336046153dbb |
| Google Colab Notebook | https://colab.research.google.com/drive/1UoySSfdO3Yeym9Sg4xEDcM5Q-blAknGh?usp=sharing |

---

## Project Overview

This project analyzes **3,072 rows** of BMW global sales data spanning **2018–2025**, covering sales volume, powertrain mix (ICE vs BEV), and macroeconomic indicators. The goal: identify what actually drives BEV adoption — energy prices or economic growth?

**Business question:**
> Which external factors most strongly influence the shift toward battery electric vehicles in BMW's global sales mix?

## Key Findings

1. **Fuel Price Index strongly correlates with BEV Share (r = 0.95).** As fuel prices rise, the share of electric vehicles in total sales rises almost in lockstep — energy cost is the dominant adoption driver.
2. **GDP Growth shows near-zero correlation with BEV Share.** Macroeconomic growth is *not* a meaningful predictor of EV adoption.
3. **Implication:** EV adoption strategy should be anchored to energy price sensitivity, not macroeconomic outlooks.

## Methodology

1. **Data Preparation** — cleaning, type casting, and validation with Pandas
2. **Exploratory Data Analysis** — trend analysis of sales volume and powertrain mix over time
3. **Correlation Analysis** — Pearson correlation between BEV Share and external indicators (Fuel Price Index, GDP Growth)
4. **Visualization & Reporting** — interactive dashboard built in Looker Studio; findings presented in a 16-slide deck for the BNSP assessment

## Tools & Stack

- **Python** — Pandas, NumPy (data preparation & analysis), correlation testing
- **Looker Studio** — interactive dashboard
- **Google Colab Notebook** — analysis workflow & documentation

## Repository Structure

```
├── data/                  # Dataset (raw & cleaned)
├── notebooks/
│   └── bmw_analysis.ipynb # Main analysis notebook
├── assets/                # Dashboard screenshots & charts
└── README.md
```
