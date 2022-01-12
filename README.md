# Loan_Approval_Prediction
Used five models of Machine learning to predict either the loan will be granted or not using different factors:
1. Gender
2. Married
3. Dependents
4. Education
5. Self_Employed 
6. ApplicantIncome
7. CoapplicantIncome
8. LoanAmount
9. Loan_Amount_Term
10. Credit_History
11. Property_Area

# Response Variable: Loan Status
 
Models and thier accuracy:
--------------------
LogisticRegression:
Accuracy: 81.5217%
--------------------
KNeighborsClassifier:
Accuracy: 78.2609%
--------------------
MLPClassifier:
Accuracy: 80.4348%
--------------------
GaussianNB:
Accuracy: 81.5217%
--------------------
RandomForestClassifier:
Accuracy: 84.7826%

Reference:
https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.LocalOutlierFactor.html#examples-using-sklearn-neighbors-localoutlierfactor
https://towardsdatascience.com/normalization-techniques-in-python-using-numpy-b998aa81d754
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html
https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
https://stackoverflow.com/questions/36367736/use-name-as-attribute
