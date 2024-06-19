# CreditRiskClassification

https://www.google.com/imgres?q=credit%20image&imgurl=https%3A%2F%2Fwww.balancecredit.com%2Fstatic%2Fbuild_credit-graphic-a6560d3e643091dfc8894085b5033958.png&imgrefurl=https%3A%2F%2Fwww.balancecredit.com%2Fbuild-credit%2F&docid=l6u7nes-BoTAjM&tbnid=er5bqVHuKEJZuM&vet=12ahUKEwjAj-jCjeiGAxXTCTQIHSFNDGgQM3oECBMQAA..i&w=2567&h=1711&hcb=2&ved=2ahUKEwjAj-jCjeiGAxXTCTQIHSFNDGgQM3oECBMQAA


## Making the Training and Testing Sets and Model Predictions

The columns in the credit data is divided into two components: the features(**loan_size**, **interest_ratio**, **borrower_income**, **debt_to_income**, **num_of_accounts**, **derogatory_marks**, and **total_debt**) and the label(**loan_status**). Both these components are split into training and testing sets, with 75% of the data being in the training set and the remaining 25% in the testing set. A Logistic Regression model is initialized and fitted with the features and label data in the training set. The model is then used to predict labels when it is provided the features information in the testing set. 


## Evaluating the Model's Performance 

A confusion matrix and classification report is created using the model's prediction of the label and the actual labels in the testing set. It is concluded that the logistic regression model predicts the healthy loans and high-risk loans pretty well. The precision for the healthy loans is 100% and also has a recall of 100%. The high-risk loan values, on the other hand, are relatively lower than those of healthy loans: The precision is 87% and the recall is 95%.


The fully written Credit Risk Analysis Report can be found [here](https://github.com/palraval/CreditRiskClassification/blob/main/report.md).

