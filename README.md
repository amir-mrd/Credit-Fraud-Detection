# Credit-Fraud-Detection
## Using Machine Learning to detect Fraudulent Transactions in Credit Card Records.

In this project, we will be utilizing different predictive models to evaluate their accuracy in detecting whether a transaction is a normal payment or a fraud. The dataset we will be working with has scaled features, and the names of the features are not disclosed to maintain privacy. Despite this limitation, we can still analyze crucial aspects of the dataset.

<h3> Data: </h3>

To begin with, we need to obtain a fundamental understanding of our data. It's important to note that, due to privacy concerns, we are unaware of the specific content of the columns, except for "transaction" and "amount." However, we do know that the unknown columns have already been scaled.

<h4> in summry: </h4>
<li> The transaction amounts are relatively small, with the mean of all transactions being approximately USD 88. </li>
<li> There are no null values in the dataset, so we do not need to focus on ways to replace missing values. </li>
<li> Non-fraud transactions occur 99.83% of the time, while fraud transactions only occur 0.17% of the time in the dataframe. </li>

We will use four different classifications method to detect classify the Fraud and Non-fraude transactions in our dataset:

<li> <b> Logistic Regression </b> </li>
<li> <b> K-Nearest Neighbor (KNN) </b> </li>
<li> <b> Support Vector Classifier (CSV) </b> </li>
<li> <b> Decission Tree </b> </li>



