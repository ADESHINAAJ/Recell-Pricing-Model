# Recell-Pricing-Model
Pricing model for used/refurb devices. EDA, feature engineering and linear regression with diagnostics (linearity, VIF, residuals). Interpretable coefficients inform a dynamic pricing strategy. Python, pandas, scikit-learn/statsmodels

**Commit message:** `Initial commit: E-news A/B testing notebook and README`

---

## 3) ReCell

```markdown
# ReCell: Pricing Model for Used & Refurb Devices

Predict device selling price and identify drivers for a dynamic pricing strategy.

## Overview
- **Goal:** Reliable price estimation and interpretable drivers (brand, condition, RAM, age).
- **Techniques:** EDA, Linear Regression, diagnostics (linearity, VIF, normality/heteroskedasticity).

## Data
Coursework used-devices dataset (not included).

## How to Run
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
