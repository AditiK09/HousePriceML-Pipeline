# 🏠 House Price Prediction (Regression)

This project predicts house prices using **Machine Learning regression models**.  
The final selected model is **Linear Regression**, trained using a **StandardScaler + LR Pipeline**.

---

## ✅ Project Highlights
- Data Cleaning + Preprocessing
- Exploratory Data Analysis (EDA)
- Train-Test split evaluation
- Model comparison:
  - Linear Regression ✅ (Best)
  - Ridge Regression (Tuned)
  - Random Forest (Tuned)
- Regression evaluation metrics:
  - MAE, MSE, RMSE, R²
- Diagnostic plots:
  - Actual vs Predicted
  - Residual Plot
  - Residual Distribution

---

## 📌 Final Model
**Linear Regression Pipeline**
- `StandardScaler`
- `LinearRegression`

Chosen because it achieved the best test performance and gave strong interpretability.

---

## 📊 Results
| Model | MAE | RMSE | R² |
|------|-----|------|----|
| Linear Regression | 	920296.224378 | 1.235086e+06 | 0.645774 |
| Ridge (Tuned) | 917245.779532 | 	1.235350e+06 | 0.645622 |
| Random Forest (Tuned) | 	937958.932851 | 1.271906e+06 | 0.624339 |

## 🧠 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn

---


