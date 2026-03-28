# MVC Project - Multilayer Perceptron

## Student Information
| Field | Details |
|-------|---------|
| **Name** | Mujeeb Khan |
| **Roll Number** | 25I-2633 |
| **University** | FAST National University |
| **Program** | Data Science |
| **Course** | Multi-Variable Calculus |

---

## Assigned Weights

| Parameter | Value | Parameter | Value |
|-----------|-------|-----------|-------|
| w1 | -0.52 | w6 | 0.63 |
| w2 | -0.63 | w7 | 0.50 |
| w3 | 0.39 | w8 | -0.21 |
| w4 | 0.56 | w9 | 0.15 |
| w5 | -0.32 | w10 | -0.23 |
| b1 | 0.01 | b2 | -0.11 |

---

## Results

### Initial Predictions
| Sample | Prediction | True Label |
|--------|------------|------------|
| s(1) | 0.4883 | 1 |
| s(2) | 0.4885 | 1 |
| s(3) | 0.4883 | 0 |

**Initial MSE Loss:** 0.2539

### Optimizer Comparison (10 iterations)

| Iteration | Plain GD | Momentum | NAG |
|-----------|----------|----------|-----|
| 1 | 0.2539 | 0.2539 | 0.2539 |
| 5 | 0.2450 | 0.2410 | 0.2390 |
| 10 | 0.2400 | 0.2310 | 0.2270 |

**Best Optimizer:** NAG (5.4% improvement)

---

## Files
- `MLP_Project_25I2633.ipynb` - Jupyter Notebook
- `MLP_Report_25I2633.pdf` - Project Report

---

## How to Run
1. Go to https://colab.research.google.com/
2. Upload `MLP_Project_25I2633.ipynb`
3. Click **Runtime → Run all**

---

**Status:** ✅ Complete  
**Date:** March 2026
