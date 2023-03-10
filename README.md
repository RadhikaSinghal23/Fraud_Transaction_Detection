# Fraud_Transaction_Detection
The dataset chosen is a split of train test data from the credit card transactions of a labeled dataset. The objective is to build a model to flag a fraud transaction in the future. 
Main Challenges observed: 
1. Enormous data size 
2. Imbalanced classes, only 0.6% of fraud transactions. 
3. Misscliassfication should be minimal 

This project, to overcome the above challenges, relaises the importance of data pre-processing, feature engineering, handling imabalnced classes through SMOTE, Borderline SVM SMOTE, ADAYSN and compare performance with baseline data while fitting the model, apply classification models (Random Forest, Gradient Boost Trees), feature importance, hyper-parameter tuning through Bayesian Optimization with HYPEROPT, select appropriate evaluation metric (F1 score, AUC ROC, G-Mean).
