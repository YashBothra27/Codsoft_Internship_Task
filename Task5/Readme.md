Task 5 of codsoft Internship
## PROJECT NAME
CREDIT CARD FRAUD DETECTION
## PROBLEM STATEMENT
Build a machine learning model to identify fraudulent credit card transactions.
## PROJECT DESCRIPTION
1. IMPORT LIBRARIES: Importing the required python libraries for data analysis and model building. Libraries used:(Numpy,Pandas,Matplotlib,Scikit-Learn)
2. IMPORT DATASET: Import the datset and convert it into a datframe.
   Dataset source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data
3. DATAFRAME INFORMATION: Genrating basic dataframe information of datset for understanding of data. This includes the statistacl description of dataset,dataset shape,column details,Datatype.
4. DATA CLEANING AND MANIPULATION: Cleaned the dataset using pandas functions.Checked for null values,removed duplicates.
5. MODEL BUILDING: Built a machine learning model using Random forest algorithm based on the datset.Created a model piepline,defined features and target variables,handled class inbalance using SMOTE, and evaluated model.
The model generates folloing scores on execution:   
**Class 1 (Fraud) : 
Precision = 0.88, 
Recall = 0.77,
F1-score = 0.82**
