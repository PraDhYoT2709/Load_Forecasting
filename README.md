
# ⚡ Load Forecasting using XGBoost

This project focuses on forecasting electrical load using **XGBoost**, a high-performance gradient boosting algorithm. It leverages historical time series data from transformer lines to predict short-term load demand with high accuracy.

---

## 🎯 Forecasting Objective

The model aims to forecast load values for the following transformer lines and aggregated metrics:

- **kVA - 132 L3**
- **kVA - 132 L5**
- **kVA - 33**
- **Total kVA**

These forecasts help in optimizing load planning, enhancing energy efficiency, and ensuring supply-demand balance in real-world power systems.

---

## 📈 Forecasting Results

| Target           | MAE     | MAPE (unsafe) | MAPE (safe) | RMSE   | R² Score | ±5% Band Accuracy |
|------------------|----------|----------------|---------------|---------|------------|----------------------|
| **kVA - 132 L3**  | 1147.22 | 1.85%         | 3.83%        | 2581.93 | 0.79      | 75.00%             |
| **kVA - 132 L5**  | 1134.55 | 1.87%         | 3.99%        | 1883.21 | 0.77      | 75.14%             |
| **kVA - 33**      | 659.09  | 3.50%         | 3.50%        | 876.07  | 0.97      | 81.61%             |
| **Total kVA**     | 2027.10 | 2.43%         | 3.42%        | 4270.64 | 0.81      | 81.83%             |

---
