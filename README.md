# Capstone-Project (Credit Card Fraud Detection)
We were given PCA transformed data of a bank credit card fraud to maintain the privacy of the customers and was asked to build a machine learning model capable of detecting fraudluent transcations
- Checked the basic info for the data 
- Checked wether the data is skewed or not
- After checking we checekd the data was highly imbalanced we used to
   1. Simple Logistic Regression

    (i) Original Dataset(imbalanced) 
   (ii) RandomOverSampling
  (iii) SMOTE
   (iv) ADASYN
   
   2. RandomForest with RandomizedSearchCV hyperparamter tuning

    (i) Original Dataset(imbalanced)
   (ii) RandomOverSampling
  (iii) SMOTE
   (iv) ADASYN
   
   
   3. Decision Tree  with RandomizedSearchCV hyperparamter tuning

    (i) Original Dataset(imbalanced)
   (ii) RandomOverSampling
  (iii) SMOTE
   (iv) ADASYN
   
   
   4. XGBOOST  with RandomizedSearchCV hyperparamter tuning

    (i) Original Dataset(imbalanced)
   (ii) RandomOverSampling
  (iii) SMOTE
   (iv) ADASYN

- Finally after checking al the models the best one to give the best recall of 73% XGBOOST with Adasyn and we go ahead with that as we have to focus on a high recall in order to detect actual fraudulent transactions.

