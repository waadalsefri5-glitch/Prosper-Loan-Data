# Prosper-Loan-Data
Udacity Project2
#  Prosper Loan Risk, Pricing & Default Exploration

An exploratory and explanatory data analysis (EDA) project investigating credit risk pricing, principal loan sizing, default footprints, and income burdens using the Prosper loan dataset.

---

## Executive Summary
- **Risk Pricing**: Strong inverse relationship ($r = -0.64$) between `ProsperScore` and `BorrowerRate`. Higher risk scores map systematically to lower borrowing rates.
- **Structural Sizing**: Principal loan amounts (`LoanOriginalAmount`) follow distinct discrete/tiered volumes, visible as structural banding in bivariate distributions.
- **Risk Ceiling**: Extreme interest rates (~0.35) heavily concentrate in small-to-mid tiers ($0–$15k), while large loans (>$20k) exhibit tight risk-exposure ceilings.
- **Status Harmonization**: 12 complex loan statuses streamlined into 4 core operational states: `Completed`, `Current`, `Past Due`, and `Defaulted`.

---

##  Repository Structure
```text
├── part_I_exploration.ipynb        # Univariate & bivariate EDA (with jittering & density checks)
├── part_II_explanatory.ipynb       # Executive summary & polished visual storytelling
├── README.md                       # Project documentation

## Tech Stack & Libraries
Language: Python 

Data Wrangling: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook / Google Colab
