# Yandex-Practicum

**Project - Customer Churn**

*Project Description*

Customers began to leave Beta-Bank. Every month. A little, but noticeable. Banking marketers figured it was cheaper to keep current customers than to attract new ones.

It is necessary to predict whether the client will leave the bank in the near future or not. We have been provided with historical data on customer behavior and termination of agreements with the bank.

Let's build a model with an extremely large value of the F1 score - we need to bring the metric to 0.59. Then we check the F1 score on the test set.

Additionally, we measure the AUC-ROC, compare its value with the F1 score.

Data source: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

*Description of data*

*Signs*
* RowNumber - row index in the data
* CustomerId - unique customer identifier
* Surname - surname
* CreditScore - credit rating
* Geography - country of residence
* Gender - gender
* Age - age
* Tenure - how many years a person has been a bank client
* Balance - account balance
* NumOfProducts - the number of bank products used by the client
* HasCrCard - the presence of a credit card
* IsActiveMember - client activity
* EstimatedSalary - estimated salary

*Target feature*
* Exited - the fact that the client left