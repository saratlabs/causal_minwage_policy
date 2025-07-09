# 📊 Causal Inference: Minimum Wage Policy & Employment

This project simulates and evaluates the **causal impact of a minimum wage policy** on regional employment rates using both:

- ✅ Classical Econometrics: Difference-in-Differences (DiD) via OLS
- 🤖 Machine Learning for Causal Inference: Double Machine Learning (DML) from EconML

---

## 🎯 Objective

To estimate the **Average Treatment Effect (ATE)** of a policy introduced in 2020 that affected only one region (Treated), while another region remained unaffected (Control). This project is part of my **Econometric Modeling portfolio**.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `notebook.ipynb` | Full analysis pipeline (data simulation → causal estimation) |
| `employment_rate_trend.png` | Plot showing pre/post employment rate trends |
| `ols_did_summary.txt` | OLS model output from DiD regression |
| `estimated_ate.csv` *(optional)* | ATE estimated using EconML's DML |

---

## 🧠 Methods Used

- **Simulated Panel Dataset** (2018–2021)
- `treatment`: 1 for treated region
- `post`: 1 for years ≥ 2020
- `treat_post`: interaction term = DiD effect
- **OLS Regression (DiD)**
- **Double Machine Learning (DML)** with LinearRegression

---

## 🔍 Results

- Estimated ATE ≈ **-5.50** using both OLS and DML
- The policy **reduced employment by ~5.5 percentage points** in the treated region
- `p-value < 0.01` → Strong evidence of causal effect

---

## 📦 Dependencies

Python 3.8+
pandas
numpy
matplotlib
statsmodels
scikit-learn
econml


> Note: Recommended to run this on **Google Colab** for easiest setup with `EconML`.

---

## 📂 Part of: Econometric Modeling Series

This project is maintained under the **Econometric Modeling** category, separate from my core **Super 9 ML/AI Projects**.

Econometric-Modeling/
├── causal_minwage_policy/
├── gini_income_tax_analysis/ (coming soon)
└── inflation_shock_modeling/ (coming soon)


---

## ✍️ Author

**Sai Sarat Chandra**  
 Econometrics • Causal ML • Policy Modeling

---

## 🔗 License

This project is released under the MIT License.

---
