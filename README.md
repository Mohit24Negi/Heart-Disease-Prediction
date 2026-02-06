# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview
This project focuses on building an end-to-end machine learning classification system to predict the presence of heart disease using clinical and demographic patient data. The goal is to support early diagnosis and data-driven medical decision-making by identifying key health risk factors.

## 🎯 Objective
- Analyze patient health data using Exploratory Data Analysis (EDA)
- Identify important features influencing heart disease
- Build and compare multiple machine learning models
- Select the most robust and scalable model based on performance metrics

## 📊 Dataset
- Source: Kaggle – Heart Disease Dataset  
- Records include medical attributes such as:
  - Age, Sex
  - Chest Pain Type
  - Blood Pressure
  - Cholesterol
  - ECG Results
  - Maximum Heart Rate
  - Exercise-Induced Angina

## 🔍 Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Train-Test Split  
5. Model Training  
6. Model Evaluation & Comparison  

## 🤖 Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM  
- CatBoost  

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  

> Recall and ROC-AUC were prioritized due to the medical importance of minimizing false negatives.

## 🏆 Results
- CatBoost and LightGBM achieved the best performance  
- ROC-AUC score of approximately 0.95  
- Strong recall (~0.86), ensuring reliable detection of positive cases  

## ✅ Conclusion
Boosting-based models significantly outperformed traditional classifiers. LightGBM and CatBoost proved to be the most effective, making them suitable for real-world healthcare applications where accurate and timely predictions are critical.

## 🚀 Future Improvements
- Hyperparameter tuning  
- Threshold optimization for recall  
- Feature selection  
- Model deployment using Flask or FastAPI  

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- LightGBM, CatBoost, XGBoost  

## 👤 Author
Mohit Negi  
Aspiring Data Scientist | Machine Learning Enthusiast
