# Healthcare-Readmission
Machine Learning-based analysis and prediction of hospital readmission rates using CMS healthcare data, including EDA, hypothesis testing, and predictive modeling.

# 🏥 Hospital Readmission Analysis & Prediction 


## 📌 Overview
This project analyzes and predicts hospital readmission rates using machine learning techniques. Hospital readmissions are a critical indicator of healthcare quality and efficiency.

The goal of this project is to identify key factors affecting readmissions and build predictive models to support better healthcare decision-making.

## 🎯 Objectives
- Analyze patterns in hospital readmission data  
- Identify key influencing factors  
- Perform statistical hypothesis testing  
- Build and compare machine learning models  


## 📊 Dataset
- Source: Centers for Medicare & Medicaid Services (CMS)  
- Type: Hospital-level data  
- Key Features:
  - State  
  - Medical Condition (Measure Name)  
  - Number of Discharges  
  - Excess Readmission Ratio  

## 🧹 Data Preprocessing
- Removed irrelevant columns  
- Handled missing values  
- Converted data types  
- Removed duplicates  
- Outlier detection using IQR method  


## 📈 Exploratory Data Analysis (EDA)
- Most hospitals have readmission ratio near **1.0**  
- Significant variation across states  
- Certain conditions show higher readmission rates  
- Weak relationship between hospital size and readmission  


## 📊 Hypothesis Testing
We applied statistical tests based on variable types:

## 🤖 Machine Learning Models
- Linear Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  

## 📉 Results
- Mean Readmission Ratio ≈ 1.0018  
- Most hospitals perform near expected levels  
- Linear Regression performed competitively  
- Complex models showed limited improvement  

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- SciPy  

## 👨‍💻 Team Members
- **Om Patel**  
- **Krupa Patel**  
- **Vishal Sharma**  


## 📌 Conclusion
This project demonstrates how data analysis and machine learning can be applied to improve healthcare outcomes by understanding and predicting hospital readmission behavior.

