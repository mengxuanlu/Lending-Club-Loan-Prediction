# Lending-Club-Loan-Prediction

LendingClub is a peer-to-peer lending company, headquartered in San Francsico, California. It enables borrowers to create unsecured personal loans between $1,000 and $40,000. Investors were able to view the loan book on LendingClub website and complete their own analysis to determine the quality of the book based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. 

## Project Goal:

The goal of this project is to predict loan status, whether the borrower will pay off the loan. I use the data from 2012 to 2014 to train the model and predict the loan status for a new dataset from year 2015.

## Data Source:

https://www.kaggle.com/wordsforthewise/lending-club

## Exploratory Data Analysis

By grouping the loan status and plotting some related features, I had a further insights on the dataset.

## Feature Engineering

The dataset includes 152 features. In the data cleaning step, I reduced the features to 41 based on my personal knowledge.

## Modelling

The models I tried for comparision are Random Forest, Logistic Regression, KNN, XGboost. And I ran the confusion matrix after each model to compare the model accuracy. In the end, I selected the XGboost as my best model to fit in the 2015 dataset to predict.  

## Conclusion

From the confusion matrix result, I gave suggestions about model selection if investors want to balance risk and return when they choose the borrowers. 
