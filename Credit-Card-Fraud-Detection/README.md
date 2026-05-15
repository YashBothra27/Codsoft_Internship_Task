# Credit Card Fraud Detection

### Project Overview
This project aims to identify fraudulent credit card transactions using machine learning techniques. The workflow includes data preprocessing, handling class imbalance, exploratory data analysis, and building a classification model capable of detecting fraud transactions accurately.

This project was developed as part of the **CodSoft Internship (Task 5)**.

---

## Problem Statement
Build a machine learning model to identify fraudulent credit card transactions.
Preprocess and normalize the transaction data, handle class imbalance issues, and split the dataset into training and testing sets.
Train a classification algorithm, such as Logistic Regression or Random Forests, to classify transactions as fraudulent or genuine.

Evaluate the model’s performance using metrics like Precision, Recall, and F1-score, and apply techniques like oversampling or undersampling for improving results.

---

## Dataset
- Source: Kaggle Credit Card Fraud Detection Dataset  
- Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud  
- Contains transaction details made by credit cards  
- Highly imbalanced dataset with very few fraudulent transactions  
- Target Variable: **Class**
  - `0` → Genuine Transaction  
  - `1` → Fraudulent Transaction  

---

## Steps Performed

### 1. Import Libraries
Imported required Python libraries for:
- Data analysis
- Data preprocessing
- Data visualization
- Machine learning model building

---

### 2. Import Dataset
- Loaded the dataset into a Pandas DataFrame
- Examined dataset structure and dimensions
- Verified column information

---

### 3. Data Understanding
Performed:
- Statistical summary generation
- Dataset shape inspection
- Data type checking
- Fraud vs genuine transaction analysis

---

### 4. Data Cleaning & Preprocessing
- Checked for missing values
- Removed duplicate records
- Normalized transaction-related features
- Prepared data for machine learning

---

### 5. Handling Class Imbalance
Since the dataset is highly imbalanced:
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**
- Balanced fraudulent and non-fraudulent transaction classes
- Improved model learning capability

---

### 6. Exploratory Data Analysis (EDA)
Performed analysis and visualization on:
- Fraudulent transaction distribution
- Transaction amount behavior
- Correlation between variables
- Class imbalance visualization

---

### 7. Model Building
Built a machine learning classification model using the **Random Forest Algorithm**.

### Model Workflow
- Defined features and target variable
- Split dataset into training and testing sets
- Applied SMOTE for balancing classes
- Trained Random Forest classifier
- Evaluated model performance

---

## Model Performance

### Fraud Class (Class 1)
| Metric | Score |
|---|---|
| Precision | 0.88 |
| Recall | 0.77 |
| F1-Score | 0.82 |

The model demonstrated strong capability in detecting fraudulent transactions while minimizing false positives.

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Imbalanced-learn (SMOTE)   

---

## Key Insights
- The dataset was highly imbalanced, making fraud detection challenging.
- Applying SMOTE significantly improved fraud detection performance.
- Random Forest performed effectively for classification tasks.
- Precision and Recall metrics were more important than accuracy due to class imbalance.
- Fraudulent transactions represented only a very small portion of total transactions.

---

## Conclusion
This project successfully demonstrated the use of machine learning techniques for detecting fraudulent credit card transactions. By applying preprocessing techniques, handling class imbalance using SMOTE, and training a Random Forest classifier, the model achieved strong fraud detection performance.

---

## Author
**Yash Kumar Bothra**