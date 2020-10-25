# Credit Card Fraud Detection

**Context:** It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

**Content:** The dataset contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the original features and more background information about the data is not provided. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

**Data Source:** https://www.kaggle.com/mlg-ulb/creditcardfraud/home

For building the model, we have used an Artificial Neural Network. Please use the link below for an explanation of the basics of an Artificial Neural Network:

https://github.com/MohitGoel92/Will-the-customer-leave-the-bank-

# Conclusion

Our model has given us an accuracy of over 99%. With this, we have an algorithm that can help predict whether a credit card transaction is fraudulent. However, the data is highly unbalanced as only 0.2% of the dataset accounts for the positive class (fraud). Taking into consideration the recall score of 79%, this indicates that around 79% of fraudulent cases were correctly detected. The precision score of 84% indicates that 14% of the transactions that were predicted to be fraudulent were actually not fruadulent. This metric may be interpreted as the extra work load the department had to deal with or the amount of customers that were unnecessarily contacted/made to worry. Depending on the nature of the company, this metrics may influence the usability of the model. Using the approach of undersampling, we got an accuracy of 92%. However, when using the model to predict the whole dataset 

Our model has given us an accuracy of around 63%. With this, we have an algorithm that can help predict whether or not a user will complete the e-signing step of the loan application. One way to leverage this model is to target those predicted to not reach the e-sign phase with customised onboarding. This means that when a lead arrives from the marketplace, they may receive a different onboarding experience based on how likely they are to finish the general onboarding process. This can help our company minimise how many people drop off from the funnel. This funnel of screens is as effective as we, as a company, build it. Therefore, user drop-off in this funnel falls entirely on our shoulders. So, with new onboarding screens built intentionally to lead users to finalise the loan application, we can attempt to get more than 40% of the predicted not to finish the process to complete the e-sign step. If we can do this, then we can drastically increase profits. Many lending companies provide hundreds of loans every day, gaining money from each one. As a result, if we can increase the number of loan takers, we are increasing profits with this model. Although simple models may not be perfect, they can surely indicate where/how the company's finite resources may be reallocated to improve profits.
