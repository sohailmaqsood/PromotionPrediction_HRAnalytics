# PromotionPrediction_HRAnalytics
Whether an employee will get promoted at the end of appraisal cycle or not, this project predicts the same using various classification algorithms.
Validation is done using f-score and accuracy, using Stratified K Fold validation. Due to data imbalance, RandomUnderSampler has also been used.

Its used two algorithms - Logistic Regression and Decision Tree
I found decision tree to have better f1 score and accuracy, hence continued with the same.

Data is high imbalanced. So used imblearn library to balance.
Used StratifiedKfoldvalidation to validate the data.

This project was done under Analytics Vidhya Hackaton
