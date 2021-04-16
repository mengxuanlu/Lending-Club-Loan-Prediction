# Lending-Club-Loan-Prediction

LendingClub is a peer-to-peer lending company, headquartered in San Francsico, California. It enables borrowers to create unsecured personal loans between $1,000 and $40,000. Investors were able to view the loan book on LendingClub website and complete their own analysis to determine the quality of the book based on the information supplied about the borrower, amount of loan, loan grade, and loan purpose. 

## Project Goal:

The goal of this project is to predict loan status, whether the borrower will pay off the loan. I use the data from 2012 to 2014 to train the model and predict the loan status for a new dataset from year 2015.

## Data Source:

https://www.kaggle.com/wordsforthewise/lending-club

## Exploratory Data Analysis

By grouping the loan status and plotting some related features, I had a further insights on the dataset.

## Feature Engineering

The dataset includes 152 features. In the data cleaning step, I reduced the features to 92, and I used Boruta package to select 41 important features.

## Modelling

The models I tried for comparision are Random Forest, Logistic Regression, KNN, XGboost. XGboost gave me the highest accuracy rate, which is 99.88%. I chose this model to predict 2015 loan status, which gave me 99.80% accuracy rate. This shows this model is very reliable.

