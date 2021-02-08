# Capstone Project: Starbucks Offer Predictions
This repository contains my codes and report for Udacity's Machine Learning Engineer Nanodegree Capstone project.

## Contents
- Installation
- Project Motivation
- Project Summary
- Project Results

## Installation
Packages required for this project include pandas, numpy, matplotlib, seaborn

## Project motivation
My work at previous company was to analyze users' behaviors and predict their churn rate or buying intention on the mobile applications, which is similar to this project, and that is the main reason why I chose this as my final project for the Nanodegree program.

## Project Summary
In this project, I built separate models for each valid offers (8 in total) to predict whether a customer will complete the offer or not. After that I further calculated the probability that a customer will complete each offer and the one with the highest probability will be my final pick for that customer.

## Project Results
I tried Naive Bayes, SVM, KNN, Decision Tree, and Random Forest, and finally picked Decision Tree as final algorithm, because it produced accuracy score of above 95% for all models. The most important feature affecting whether a customer will complete an offer is the amount of money he/she spent after receiving that offer.
