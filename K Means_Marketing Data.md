The bank has extensive data on their customers for the past 6 months. 

The marketing team at the bank wants to launch a targeted ad marketing campaign by dividing their customers into at least 3 distinctive groups.  



Understanding Dataset and variables



\# CUSTID: Identification of Credit Card holder 

\# BALANCE: Balance amount left in customer's account to 

make purchases

\# BALANCE\_FREQUENCY: How frequently the Balance is 

updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)

\# PURCHASES: Amount of purchases made from account

\# ONEOFFPURCHASES: Maximum purchase amount done in one-go

\# INSTALLMENTS\_PURCHASES: Amount of purchase done in installment

\# CASH\_ADVANCE: Cash in advance given by the user

\# PURCHASES\_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)

\# PURCHASES\_FREQUENCY: How frequently 

the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)

\# ONEOFF\_PURCHASES\_FREQUENCY: How 

frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)

\# PURCHASES\_INSTALLMENTS\_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)

\# CASH\_ADVANCE\_FREQUENCY: How 

frequently the cash in advance being paid

\# CASH\_ADVANCE\_TRX: Number of Transactions made with "Cash in Advance"

\# PURCHASES\_TRX: Number of purchase 

transactions made

\# CREDIT\_LIMIT: Limit of Credit Card for user

\# PAYMENTS: Amount of Payment done by user

\# MINIMUM\_PAYMENTS: Minimum amount of 

payments made by user  

\# PRC\_FULL\_PAYMENT: Percent of full payment paid by user

\# TENURE: Tenure of credit card service for user





K-MEANS INTUITION 

* K-means is an unsupervised learning algorithm (clustering).
* K-means works by grouping some data points together (clustering) in an unsupervised fashion.  
* The algorithm groups observations with similar attribute values together by measuring the Euclidian distance between points.



K-MEANS ALGORITHM STEPS 



1. Choose number of clusters “K”
2. Select random K points that are going to be the centroids for each cluster
3. Assign each data point to the nearest centroid, doing so will enable us to create “K” number of clusters 
4. Calculate a new centroid for each cluster
5. Reassign each data point to the new closest centroid
6. Go to step 4 and repeat.







