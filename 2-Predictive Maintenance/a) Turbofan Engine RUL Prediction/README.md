
# 🚀 Turbofan Engine Remaining Useful Life (RUL) Prediction

**Domain:** Predictive Maintenance  
**Company:** Uniconverge Technologies pvt. ltd. (UCT)  
**Intern:** Samarth Ghare  
**Project:** UCT-ML Internship – Project 6  

---

## 📌 Project Overview

This project focuses on predicting the Remaining Useful Life (RUL) of aircraft turbofan engines based on sensor data collected during operational cycles. Using multivariate time series data from NASA's C-MAPSS dataset, the goal is to develop a machine learning model that can predict how many cycles an engine will operate before failure.

---

## 🎯 Problem Statement

Given engine run-to-failure data from multiple units with different operational conditions and wear levels, develop a model that accurately estimates the number of operational cycles remaining (RUL) before system failure.

---

## 📊 Dataset: C-MAPSS (FD001 Subset)

- 100 engines in training
- 100 engines in testing
- Each engine has multiple cycle records with:
  - 3 operational settings
  - 21 sensor measurements
- Test RUL values provided separately

📂 Files Used:
- `train_FD001.txt`
- `test_FD001.txt`
- `RUL_FD001.txt`

📎 Dataset Source:  
[NASA Prognostics Data Repository](https://www.nasa.gov/content/prognostics-center-of-excellence-data-set-repository)

---

## ⚙️ Approach

1. **Data Preprocessing**:
   - Parsed engine cycles and sensor values
   - Calculated true RUL for training and test sets
   - Removed low-variance/unimportant sensors

2. **Modeling**:
   - Used **Random Forest Regressor** for its robustness and interpretability
   - Trained on sensor values to predict RUL

3. **Evaluation Metrics**:
   - RMSE (Root Mean Square Error)
   - MAE (Mean Absolute Error)
   - R² Score

---

## ✅ Model Performance

| Metric | Value |
|--------|-------|
| RMSE   | 34.09 |
| MAE    | 24.73 |
| R²     | 0.33  |

---

## 📈 Visualization

Model predictions were visualized using Matplotlib to compare predicted vs. actual RUL values on the test engines.

---

## 📦 Project Files

- `Turbofan_RUL_Predict.ipynb` – Full notebook implementation
- `Project_Report.docx` – Detailed technical report
- `Project_Presentation.pptx` – Summary slides
- `README.md` – Project overview and instructions

📁 **Note**: Dataset files (`.txt`) are large and not uploaded here. Download them from the [C-MAPSS official source](https://www.nasa.gov/content/prognostics-center-of-excellence-data-set-repository) or [Google Drive link](#).

---

## 🧠 Learnings

- Hands-on experience with time-series data preprocessing
- Gained insights into sensor-based degradation modeling
- Understood importance of model selection and evaluation for regression tasks in predictive maintenance

---

## 🤝 Acknowledgments

This project was completed as part of the **UCT Machine Learning Internship Program**.

---

