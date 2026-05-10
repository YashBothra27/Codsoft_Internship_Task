TASK 2 OF CODSOFT INTERNSHIP

## PROJECT NAME
MOVIE RATING PREDICTION

## PROBLEM STATEMENT
Build a model that predicts the rating of a movie based on
features like genre, director, and actors.

## PROJECT EXPLAINATION

1. IMPORTING LIBRARIES:- the first step involves importing differnt python libraries for data analysis and model building. The libraries used are Pandas,numpy,Scikitlearn.
2. IMPORTING DATA:- The next step is to import dataset. we import the csv file and store the data as a dataframe.
   Dataset:- https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies
3. DATAFRAME INFORMATION:- After creating a dataframe,We generate some information about the dataframe like Basic dataframe information,column name,datatype of columns,dataframe shape,
4. DATA CLEANING:-No this step is about cleaning and organizing the data.We first check for null values and then drop the null values. also organize the data by stripping the hitespaces,extracting the numerical columns.
5. MODEL BUILDING:- The final and important step the model building for prediction. We use the random forest algorithm to build a model. This step involves different steps like defining features and target,preprocessing and building model piepline,training the model and Evaluating model using statistical methods like R^2 score,MSE.
   Model Prediction:We also give some dummy inputs to check the prediction of our model.
   After running the model, Our model gives the following scores
   R^2 score: 0.18
   MSE: 1.51
   Predicted score for sample data: 6.60
  
