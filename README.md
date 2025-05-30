# CardioCare-Heart-Disease-Classification
# 🫀 Cardiovascular Disease Detection using Machine Learning

This project applies machine learning techniques to enable early detection of cardiovascular diseases (CVDs) using clinical features derived from multiple datasets. Early intervention can significantly reduce morbidity and improve resource efficiency in healthcare.


## 📌 Problem Statement

Cardiovascular diseases pose a major global health challenge. Detecting heart-related conditions early through data-driven insights can greatly enhance treatment outcomes and save lives.


## 🎯 Project Objectives

- Detect the likelihood of heart disease using patient clinical attributes.
- Provide insights through exploratory data analysis and interactive visualizations.
- Enable healthcare professionals and researchers to identify high-risk patients.


## 📊 Dataset Information

- **Source**: Combination of 5 datasets from Kaggle  
- **Dataset Link**: [https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Total Observations**: 1190  
- **Duplicates Removed**: 272  
- **Final Dataset**: 918 observations  
- **Target Variable**: `HeartDisease` (1 = Heart Disease, 0 = Normal)

### 🔑 Attributes Used
- Age
- Sex
- ChestPainType (TA, ATA, NAP, ASY)
- RestingBP
- Cholesterol
- FastingBS
- RestingECG
- MaxHR
- ExerciseAngina
- Oldpeak
- ST_Slope


## 🔍 Data Analysis Highlights

- **Skewed Variables**: RestingBP (left-skewed), Cholesterol & Oldpeak (right-skewed)
- **Zero Values**: Found in Cholesterol and Oldpeak
- **Class Distributions**:
  - 54% of patients were asymptomatic
  - 76% had Fasting Blood Sugar > 120 mg/dL


## 📈 Data Visualization Dashboard

An interactive dashboard allows users to:
- Explore scatter plots between any two features
- Visualize age distributions grouped by heart disease status
- Understand gender-wise distribution and chest pain types


## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Dashboard**: Dash / Streamlit
- **Notebook Tool**: Jupyter


