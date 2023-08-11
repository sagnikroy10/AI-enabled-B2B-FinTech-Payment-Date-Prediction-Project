# AI-enabled-B2B-FinTech-Payment-Date-Prediction-Project

# Introduction
The B2B world operates differently from the B2C or C2C world. Businesses work with other businesses on credit. When a buyer business orders goods from the seller business, the seller business issues an invoice for the same. 

This invoice for the goods contains various information like the details of the goods purchased and when it should be paid. This is known in accounting terminology as “Accounts Receivable”. Seller business interacts with various businesses and sells goods to all of them at various times. 

Hence, the seller business needs to keep track of the total amount it owes from all the buyers. This involves keeping track of all invoices from all the buyers. Each invoice will have various important fields like a payment due date, invoice date, invoice amount, baseline date etc. 

# Problem Statement
The buyer business needs to clear its amount due before the due date. 
However, in real-world scenarios, the invoices are not always cleared i.e.. paid in full amount by the due date. 

The date on which a customer clears the payment for an invoice is called the payment date

Build a Machine Learning Model to predict the payment date of an invoice when it gets created in the system.

# Objectives 
In the ideal world, the buyer business should payback within the stipulated time (i.e. the Payment Term). However, in the real world, the buyer business seldom pays within their established time frame, and this is where the Account receivables Department comes into picture.

Every business consists of a dedicated Account receivables Department to collect and track payment of invoices.
It consists of an Account receivables team that is responsible for:

Collecting payments from customers for their past due invoices and sending reminders and follow ups to the customers for payments to be made.

# Methodology
We are provided with an invoices dataset which we were need to parse and process.  Then we were supposed to apply feature engineering techniques to extract patterns and identify features for efficient modelling. 

An Invoices dataset that contains the past payment information and behaviour of various buyers. 
Based on the previous payment patterns, the ML model needs to predict what will be the date a payment is made by the customer for an invoice. 

The model also needs to predict which aging bucket the invoice falls into based on the predicted payment date.

![Picture1](https://github.com/sagnikroy10/AI-enabled-B2B-FinTech-Payment-Date-Prediction-Project/assets/79736382/e48b25d3-27a0-4175-ac19-d6a72f40c1a3)

# Realistic Constraint
Availability of adequate data from the company’s database.

Hyper parameter tuning and parameters for model training including feature selection process can vary from user to user, which can result in diverse outcomes.

# Conclusion
The dataset was processed and feature engineering process were applied on it. Then it was applied on multiple machine learning models (Linear Regression, Decision Tree Regressor, XGB Regressor, Random Forest Regressor, Support Vector Regression) to find the best MSE. 

Finally, the XGB Regressor model was used to predict the payment date from the given dataset.


