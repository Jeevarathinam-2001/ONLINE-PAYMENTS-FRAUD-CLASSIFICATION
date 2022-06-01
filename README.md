# ONLINE-PAYMENTS-FRAUD-CLASSIFICATION
The objective here is to identify whether a given online transaction is valid or fradulent, so this boils down to a binary classification problem. 
The models used for classification are:
1) Logistic Regression
2) Random Forest Classifier
3) XG Boost Classifier
4) Support Vector Classifier

Dataset Description:
Dataset Link: https://www.kaggle.com/code/tijelm/online-payment-fraud-detection-eda-classification/data

No of rows: 4599270
No of columns: 10
Column Description:
step: represents a unit of time where 1 step equals 1 hour
type: type of online transaction
amount: the amount of the transaction
nameOrig: customer starting the transaction
oldbalanceOrg: balance before the transaction
newbalanceOrig: balance after the transaction
nameDest: recipient of the transaction
oldbalanceDest: initial balance of recipient before the transaction
newbalanceDest: the new balance of recipient after the transaction
isFraud: fraud transaction

Evaluation metrics used 
1) Confusion matrix
2) Classification report
3) Accuracy score
4) F1 Score
5) Log Loss

By comparing the five different evaluation metrics for each model we come to the conclusion that both XG Boost Classifier and Random forest Classifiers are the best models for classification of the big dataset.
