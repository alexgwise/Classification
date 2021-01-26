# Classification

## Credit Risk Resampling Questions ##

**1) Which model had the best balanced accuracy score?**

The SMOTEENN and SMOTE both had a balanced accuracy score of 99.47%, while the oversampling method had the lowest, though still very respectable score of 98.93%

**2) Which model had the best recall score?**

The SMOTEENN and SMOTE models also had the highest recall scores. Each model had a 99% recall, though SMOTE and SMOTEENN were slightly higher on the high risk recall measurement.

3) Which model had the best geometric mean score?

Each model had a combined geometric mean of 99%


## Credit Risk Ensemble Questions ##

**1) Which model had the best balanced accuracy score?**

The Random Forest model had the higher balanced accuracy score at 99.6%, however
it should be noted that the model was very accurate in identifying low risk loans
but not accurate in identifying the more costly high risk loans.

**2) Which model had the best recall score?**

The Easy Ensemble Classifier model has the stronger recall score averaging 94%. 
The recall for this model was much high in measuring high risk loans.

**3) Which model had the best geometric mean score?**

The EEC model had a geometric mean of 93% compared to the much lower GMS of 57% for the random forest model. 

**4) What are the top three features?**

Not surprisingly, the top 3 features were related to loan payments. "total_rec_prncp",
"total_pymt", and "total_pymnt_inv" were the highest rated features from the data set. 
