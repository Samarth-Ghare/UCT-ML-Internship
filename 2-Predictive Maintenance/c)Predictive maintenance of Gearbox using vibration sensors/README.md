
# Project 8: Predictive Maintenance of Gearbox using Vibration Data

**Company:** Uniconverge Technologies Pvt. Ltd.  
**Intern:** Samarth Ghare  
**Duration:** 6 Weeks  
**GitHub:** [Samarth-Ghare](https://github.com/Samarth-Ghare)

## 📌 Project Overview
In the manufacturing industry, gearboxes are vital for transmitting power. Unexpected gearbox failures can result in costly downtime. This project applies machine learning to predict gearbox faults using vibration signals collected from four sensors.

## 🎯 Problem Statement
Develop a machine learning model that distinguishes between a healthy gearbox and one with a broken tooth using vibration data.

## ⚙️ Data Description
- Collected using SpectraQuest's Gearbox Fault Diagnostics Simulator
- Two classes: Healthy and Broken Tooth
- 4 vibration sensors
- Data stored as `.txt` files

## 🛠️ Methodology
- Extracted time-domain features:
  - Mean, Standard Deviation, RMS, Max, Min, Skewness, Kurtosis
- Features per sample: 28 (7 features × 4 sensors)
- Model: Random Forest Classifier
- Evaluation: Confusion Matrix, Accuracy, Classification Report

## ✅ Results
- **Accuracy:** 100%
- **Perfect classification** for both classes (Healthy and Broken)
- Model evaluated using test data (80-20 split)

## 📚 Learnings
- Handling of multi-sensor vibration data
- Signal feature engineering
- Model development for predictive maintenance

## 🚀 Future Work
- Add frequency-domain features using FFT
- Test deep learning models (CNN, LSTM)
- Deploy model to edge hardware for real-time monitoring

## 📂 Repository Structure
```
Project8/
├── Healthy Data/
├── BrokenTooth Data/
├── Project8.ipynb
├── gearbox_model.pkl
├── README.md
├── Project8_Report_UCT.pdf
├── Project8_Gearbox_Presentation.pptx
```

## 📎 License
This project is submitted as part of a Machine Learning Internship at **Uniconverge Technologies Pvt. Ltd.**

---

