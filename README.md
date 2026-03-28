# 🦄 Global Unicorn Companies: Valuation & Growth Efficiency Audit

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> **Project Profile:** Venture Capital & Market Analysis  
> **Domain:** Financial Data Analytics | EDA | Business Intelligence  
> **Tech Stack:** Python · Pandas · Seaborn · Matplotlib

---

## 📌 Executive Summary

This project analyzes the global landscape of **Unicorn companies** — private startups valued at over $1 billion USD. The goal was to identify market concentration patterns by industry and geography, audit the dataset for categorical inconsistencies, and develop a custom KPI called **"Years to Unicorn"** to measure capital efficiency across sectors.

**Key questions answered:**
- Which industries produce unicorns the fastest?
- How concentrated is global unicorn capital geographically?
- Where do data quality issues hide in financial datasets?

---

## 📁 Project Structure

```
unicorn-companies-valuation-audit/
│
├── unicorn_companies.ipynb   # Main analysis notebook
├── README.md
└── .gitignore
```

---

## 📊 Dataset

| Field | Detail |
|---|---|
| Source | [Kaggle – Unicorn Companies Dataset](https://www.kaggle.com/) |
| Scope | Global unicorn companies (valued $1B+) |
| Key columns | Company, Valuation ($B), Founded Year, Unicorn Year, Industry, Country |

> ⚠️ *Update the source link above with the exact Kaggle URL used.*

---

## 🧹 Data Cleaning & Integrity Audit

| Step | Action |
|---|---|
| **Normalization** | Standardized industry labels (e.g., unified "Artificial Intelligence" variants) for accurate aggregation |
| **Financial Formatting** | Converted string-based valuation fields (`$XB`) into numerical floats for quantitative modeling |
| **Schema Validation** | Identified and corrected column reference errors (`Country/Region`) via structural dataframe audit |

---

## 💡 Strategic Business Insights

### 🌍 Geographical Dominance
The United States and China account for the vast majority of global unicorn capitalization, reflecting a high concentration of venture capital in these two hubs. Other regions remain significantly underrepresented.

### ⚡ Capital Velocity (KPI: Years to Unicorn)
Custom KPI developed to measure how fast each industry reaches billion-dollar valuations:

| Industry | Avg. Years to Unicorn | Market Signal |
|---|---|---|
| Auto & Transportation | ~5 years | 🔥 High heat |
| Artificial Intelligence | ~6 years | 🔥 High heat |
| Health | ~8+ years | 🧊 Long-term |
| Consumer & Retail | ~8+ years | 🧊 Long-term |

### 🔍 The "Other" Category Opportunity
The `Other` industry bucket holds significant cumulative valuation, suggesting the need for deeper sub-sector classification (e.g., Aerospace, SpaceTech, CleanEnergy).

---

## 🎯 Stakeholder Recommendations

- **Short-term / liquidity-focused investors:** Prioritize **AI and Fintech** — shortest maturity cycles, highest capital velocity.
- **Long-term / impact investors:** **Health and Consumer** sectors require patient capital but offer stable growth trajectories.
- **Data governance:** Recommend adopting a standardized industry taxonomy (e.g., GICS or CB Insights tiers) to eliminate classification noise in future datasets.

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/facurboll/unicorn-companies-valuation-audit.git
cd unicorn-companies-valuation-audit

# 2. Install dependencies
pip install pandas seaborn matplotlib jupyter

# 3. Launch the notebook
jupyter notebook unicorn_companies.ipynb
```

---

## 👤 Author

**Facundo Ramirez Boll**  
Public Accountant & Data Analyst 🇦🇷  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/facundo-ramirez-boll-37849a227)
[![GitHub](https://img.shields.io/badge/GitHub-facurboll-black?logo=github)](https://github.com/facurboll)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
