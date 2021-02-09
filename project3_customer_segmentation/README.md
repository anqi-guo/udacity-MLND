# Capstone Project: Starbucks Offer Predictions
This repository contains my codes and report for Udacity's Machine Learning Engineer Nanodegree Capstone project.

## Contents
- Project Motivation
- Project Summary
- Project Results

## Project motivation
My work at previous company was to analyze users' behaviors and predict their churn rate or buying intention on the mobile applications, which is similar to this project, and that is the main reason why I chose this as my final project for the Nanodegree program.

## Project Summary
In this project, I first clean the 3 datasets and then combine them into one big dataframe, and then create a bunch of new features, and finally build a predictive model to find the best offer for each customer. 

## Project Results
I tried Naive Bayes, Decision Tree, and Gradient Boosting Decisiont Tree, and finally picked GBDT as final algorithm, because it produced accuracy score of 83% which is acceptable. The most important features are the number of offers received, the amount of money spent after viewing the offer, and the time difference between viewing the offer and making transactions.
