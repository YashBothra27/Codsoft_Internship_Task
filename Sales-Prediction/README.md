# Task 4 – Sales Prediction Using Python

### Introduction
This project focuses on predicting product sales using advertising expenditure data from different media channels such as TV, Radio, and Newspaper. The main objective is to analyze how advertising budgets influence sales and to build a machine learning model capable of accurately predicting future sales values.
This project was completed as part of the CodSoft Internship – Task 4.

---

## About the Dataset
The dataset contains advertising spending data across multiple marketing platforms along with corresponding sales figures.
Dataset obtained from Kaggle:  
https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input

---

## Problem Statement
The goal of this project is to develop a machine learning model that predicts product sales based on advertising expenditure across TV, Radio, and Newspaper channels.

---

## Steps Performed

### 1. Importing Libraries
Imported essential Python libraries for:
- Data analysis
- Data visualization
- Machine learning model building

---

### 2. Importing Dataset
- Loaded the dataset into a Pandas DataFrame
- Checked rows and columns
- Verified dataset structure

---

### 3. Data Understanding & Analysis
Performed:
- Dataframe inspection
- Statistical summary generation
- Data type checking
- Missing value verification

---

### 4. Exploratory Data Analysis (EDA)
Conducted basic analysis such as:
- Average advertising spend
- Total advertising spend
- Relationship between advertising channels and sales
- Performed visualizations
---

### 5. Model Building
Built a **Linear Regression Model** to predict sales using advertising expenditure data.


- Defined features and target variable
- Split dataset into training and testing sets
- Created machine learning pipeline
- Trained the Linear Regression model
- Evaluated model performance using regression metrics

---

## Model Output

### Evaluation Metrics

| Metric | Score |
|---|---|
| Mean Squared Error (MSE) | 2.91 |
| Mean Absolute Error (MAE) | 1.27 |
| R² Score | 0.91 |

The model achieved an **R² Score of 0.91**, indicating excellent predictive performance and a strong relationship between advertising expenditure and sales.

---

## Tools & Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Key Insights
- TV advertising showed the strongest impact on sales.
- Radio advertising also contributed significantly to product sales.
- Newspaper advertising had comparatively lower influence.
- The dataset showed strong positive relationships between advertising expenditure and sales.
- Linear Regression performed effectively for this prediction problem.

---

## Conclusion
This project successfully demonstrated how machine learning can be used for sales prediction using advertising data. By applying Linear Regression, the model achieved high prediction accuracy and effectively identified the relationship between marketing expenditure and product sales.

---

# Author
**Yash Kumar Bothra**  