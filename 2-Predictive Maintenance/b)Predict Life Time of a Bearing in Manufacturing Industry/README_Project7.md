# Project 7: Predict Life Time of a Bearing in Manufacturing Industry

**Company:** Uniconverge Technologies Pvt. Ltd.

## 📌 Background
Bearings are critical in manufacturing systems. Predicting their remaining useful life helps industries plan maintenance, avoid breakdowns, and reduce costs.

## 🧠 Problem Statement
Build a machine learning model to predict the remaining life of bearings using vibration signal data collected from test-to-failure experiments.

## 🧩 Dataset
- 3 test sets with a total of ~7,500 files
- Each file: 20,480 points, sampled at 20 kHz
- Channels: 4–8 depending on test set
- Format: ASCII
- https://drive.google.com/file/d/12rV9AhpqbMivYCu4WVM7DhXpO1aO98k_/view?usp=sharing 

## 🛠️ Approach
- Preprocessing: File reading, parsing timestamps, and label generation
- Feature Engineering: Mean, Std, Skewness, Kurtosis per signal
- Model: RandomForestClassifier
- Tools: Python, Google Colab, Pandas, NumPy, Scikit-learn, Matplotlib

## 📊 Results
- **Accuracy:** 98.66%
- High precision and recall on all three test sets
- Low false positives/negatives in confusion matrix

## ✍️ Learnings
- Signal-based feature extraction
- Working with time-series sensor data
- Applying supervised learning for predictive maintenance

---
**Developed during internship at Uniconverge Technologies Pvt. Ltd.**
