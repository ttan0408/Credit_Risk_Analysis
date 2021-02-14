# Credit_Risk_Analysis

## Objective : 
We are asked to preform the credit card risk analysis project.  This is a real-world challenge and we choose to apply machine learning to solve the challenge.
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we perform three technical analysis deliverables and a written report : The three technical analysis are : Resampling Models, the SMOTEENN Algorithm, and Ensemble Classifiers 

## Resampling Models
Reviewing the dataset from LendingClud there is class imbalance between high risk and low risk credit card with the total of 68470 low_risk application vs 347 high_risk. With this class imbalanced dataset we have to use resampling models to remove imbalance between class. These are : Naive Random Oversampling, SMOTE Oversampling, Combination Sampling. Through the sampling models and validating the Naive Random Oversampling has the best balanced accuracy score, the best recall score, and the best geometric mean score here are the summary table between the models : 

