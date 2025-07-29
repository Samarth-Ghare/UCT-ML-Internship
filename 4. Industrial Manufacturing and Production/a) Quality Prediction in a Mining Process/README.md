
# Project 10: Quality Prediction in a Mining Process

This project is part of the Machine Learning Internship with **Uniconverge Technologies Pvt. Ltd. (UCT)**.

## 📌 Objective
To predict the percentage of **silica impurity** in iron ore concentrate using real-world data from a flotation plant. The goal is to support process engineers in proactively managing ore quality to improve efficiency and reduce environmental impact.

## 🧠 Problem Statement
High silica content in ore concentrate negatively affects the mining process and leads to waste. By predicting % Silica in real-time or ahead of time, engineers can take preventive action to reduce impurity levels and optimize the output.

## 📂 Dataset
- Source: Real industrial data from a flotation plant.
- File: `MiningProcess_Flotation_Plant_Database.csv`
- Time Range: March 2017 – September 2017
- Features: Iron feed, Silica feed, Starch & Amina flow, pH, air flow and levels in multiple flotation columns.
- Target: `% Silica Concentrate` (last column)

## 🧩 Implementation
- Data Preprocessing:
  - Handled European decimal commas.
  - Converted string values to float.
  - Checked for missing and non-numeric values.
- Model:
  - Tested regression models (e.g., Linear Regression, XGBoost, Random Forest).
  - Evaluated RMSE, MAE, R² score.
  - Conducted feature importance analysis.
  - Performed multi-step forecasting.

## 📊 Results
- Achieved accurate silica concentration predictions with RandomForestRegressor.
- Feature importance indicated that `Ore Pulp pH`, `Air Flow`, and `Feed Composition` strongly influence quality.
- Model capable of minute-level and multi-hour forecasting.

## 🧠 Learnings
- Industrial datasets require deep preprocessing due to mixed sampling rates and formatting inconsistencies.
- Feature engineering and interpretability are critical in manufacturing domains.
- Predictive analytics can significantly reduce waste and improve sustainability in mining.

## 📎 Files
- `Project10.ipynb`: Full code
- `MiningProcess_Flotation_Plant_Database.csv`: Dataset
- `Report_Project10_UCT.pdf`: Detailed Report
- `Presentation_Project10_UCT.pptx`: PowerPoint Slides

---

> 🔰 Project by: **Samarth Ghare**  
> 🔗 [LinkedIn](https://www.linkedin.com/in/samarth-ghare-998452291/) | [GitHub](https://github.com/Samarth-Ghare)
