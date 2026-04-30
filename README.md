# Decision Tree, Bagging, and Random Forest Comparison

## Overview
This project compares three tree-based machine learning models—Decision Tree, Bagging, and Random Forest—on the Adult (Census Income) dataset. The goal is to analyze how ensemble methods improve performance and reduce overfitting compared to a single decision tree.

## Problem
The task is to predict whether an individual earns more than $50,000 per year based on demographic and employment-related features.

## Dataset
The dataset used is the Adult (Census Income) dataset from the UCI Machine Learning Repository.

Becker, B. & Kohavi, R. (1996). Adult [Dataset].  
https://doi.org/10.24432/C5XW20

## Preprocessing
- Handled missing values using imputation  
- Encoded categorical features using one-hot encoding  
- Split data into training and testing sets  
- No scaling applied (tree-based models do not require it)  

## Models Used
- Decision Tree  
- Bagging (ensemble of decision trees)  
- Random Forest  

## Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

## Results
- Random Forest achieved the best performance  
- Bagging improved results over a single Decision Tree  
- Decision Tree showed signs of overfitting  

## Key Insights
- Ensemble methods reduce variance and improve generalization  
- Random Forest performs best due to feature randomness and averaging  
- Overfitting is reduced when using multiple models instead of one  

## Technologies
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  

## How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Run the notebook or script to train and evaluate models.

## Conclusion
This project demonstrates that ensemble learning methods such as Bagging and Random Forest outperform a single Decision Tree by improving model stability and generalization.
