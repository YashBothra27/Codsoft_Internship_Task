# Titanic Survival Prediction

## Project Overview
This project aims to predict whether a passenger survived the Titanic disaster using machine learning. It follows a structured workflow including data cleaning, exploratory data analysis, feature engineering, and model building. This project was developed as part of the CodSoft Internship (Task1).

---

## Problem Statement
Build a machine learning model to predict passenger survival based on features such as age, gender, passenger class, and family information.

---

## Dataset
- Source: Kaggle Titanic Dataset  
- Includes passenger details like Age, Sex, Pclass, Fare, etc.  
- Target Variable: **Survived (0 = No, 1 = Yes)**  

---

## Steps Performed

### 1. Data Cleaning
- Handled missing values in **Age** and **Embarked**
- Dropped irrelevant columns: `Name`, `Ticket`, `Cabin`

### 2. Exploratory Data Analysis (EDA)
- Visualized survival patterns based on gender and passenger class
- Identified important trends and relationships in the dataset

### 3. Feature Engineering
- Created **FamilySize** feature  
- Created **IsAlone** feature  

### 4. Encoding
- Converted categorical variables:
  - `Sex` → numerical  
  - `Embarked` → one-hot encoding  

### 5. Model Building
- Used **Logistic Regression**
- Applied **Standard Scaling**
- Split data into training and testing sets  

---

## Model Performance
- **Accuracy:** 79.89%  
- Model performs slightly better at predicting non-survivors  
- Evaluated using:
  - Confusion Matrix  
  - Precision, Recall, F1-score  

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Conclusion
The model achieved around 80% accuracy, providing a strong baseline for survival prediction. The project demonstrates effective use of data preprocessing, feature engineering, and machine learning techniques.

---

## Author
Yash Bothra