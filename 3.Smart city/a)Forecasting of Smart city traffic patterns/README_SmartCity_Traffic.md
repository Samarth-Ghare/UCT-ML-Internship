
# 🚦 Smart City Traffic Forecasting (Project 9)

**Company**: Uniconverge Technologies Pvt. Ltd.

## 📌 Objective
To forecast traffic volume at four major city junctions using time-series modeling. This helps in better infrastructure planning and real-time traffic management.

## 🧠 Model Used
- Facebook Prophet (per junction forecasting)

## 📁 Dataset
- `train_aWnotuB.csv` - Historical vehicle data at junctions
- `datasets_8494_11879_test_BdBKkAj.csv` - Timestamps for prediction

## 🔁 Approach
- Trained a separate Prophet model for each of the 4 junctions.
- Forecasted `Vehicles` for corresponding test timestamps.
- Final predictions saved in `SmartCity_Traffic_Forecast.csv`.

## 📊 Results
- Successfully predicted vehicle flow for all junctions.
- Enabled pattern discovery on weekends vs weekdays.

## ✍️ Learnings
- Working with seasonal time series data.
- Importance of modeling per-location time series separately.
- Government-focused forecasting challenges.

---

_This project is a part of the Machine Learning Internship at UCT._
