# B-usiness-Analytics-and-Valuation-Project

## 📌 Overview

This project focuses on developing and evaluating a portfolio strategy that ranks stocks based on their past returns and allocates weights accordingly. The project includes data processing, ranking logic, weighting schemes, and performance evaluation across various metrics. All implementation and strategy design are based on my individual work using Python and Excel for the MFIN602 coursework.

---

## 🎯 Objectives

- Rank stocks based on historical return data for 2022.
- Assign portfolio weights proportional to the return-based ranks.
- Calculate realized returns for 2023.
- Analyze portfolio performance relative to equal-weight and benchmark portfolios.

---

## 💡 Methodology

### 1. Return Ranking

- Collected and cleaned 2022 return data from `MFIN602 Project.xlsx`.
- Ranked firms based on their prior-year returns (highest return = highest rank).

### 2. Weighting Strategy

- Applied rank-based proportional weights:  
  $$ w_i = \frac{\text{Rank}_i}{\sum \text{Ranks}} $$
- Ensured total portfolio weight = 100%.

### 3. Portfolio Return Calculation

- Used 2023 actual returns to compute:
  - Portfolio return
  - Equal-weighted return (baseline comparison)

### 4. Output and Validation

- Python notebook outputs include:
  - Ranked list of stocks
  - Assigned weights
  - Portfolio return vs. equal-weight return
- Excel workbook confirms calculations for cross-validation.

---

## 🧰 Requirements

Install required packages with:

```bash
pip install pandas numpy openpyxl
```

## 🙋 Author

**Jinyan Yong**
 Master of Finance – McMaster University