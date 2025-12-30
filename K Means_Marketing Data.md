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



# Marketing Analytics: Credit Score Customer Segmentation

A machine learning project using K-Means clustering to segment customers based on credit score and behavioral patterns for targeted marketing strategies.

## 📊 Project Overview

This project applies unsupervised machine learning techniques to segment customers into distinct groups based on their credit profiles and behavior [web:166]. The analysis enables data-driven marketing decisions by identifying customer segments with similar characteristics and risk profiles [web:167].

## 🔗 Notebook

View the full analysis: [K Means_Marketing_Credit Score.ipynb](https://github.com/Tunguyen5578/Marketing-Analytics_Case_Study/blob/7a74ff10b8ebd2e0fa5add6872342fdda1054f89/K%20Means_Marketing_Credit%20Score.ipynb)

## 🎯 Objectives

- Segment customers based on credit scores and financial behavior [web:170]
- Identify distinct customer risk profiles (high, medium, low risk) [web:169]
- Develop targeted marketing strategies for each segment [web:171]
- Optimize credit limit and product offerings based on cluster characteristics [web:169]
- Improve customer retention and lifetime value through personalized approaches [web:170]

## 🛠️ Technologies Used

- **Python Version**: 3.13 (Latest as of December 2025)
- **Core Libraries**:
  - scikit-learn - K-Means clustering algorithm
  - pandas - Data manipulation and analysis
  - numpy - Numerical computations
  - matplotlib & seaborn - Data visualization
  - scipy - Statistical analysis

## 📈 Methodology

### 1. Exploratory Data Analysis
- Understanding customer demographics and credit behavior [web:166]
- Identifying patterns in spending habits, payment history, and credit utilization [web:170]
- Missing value detection and handling [web:171]

### 2. Feature Engineering & Preprocessing
- Feature scaling and normalization [web:170]
- Handling missing values through imputation [web:171]
- Feature selection for optimal clustering performance [web:166]

### 3. Clustering Analysis
- Hopkins statistic test to assess clustering tendency [web:171]
- Elbow Method to determine optimal number of clusters (k) [web:172]
- K-Means algorithm implementation [web:168]
- Silhouette Score analysis for cluster validation [web:171]

### 4. Cluster Evaluation
- Davies-Bouldin Index assessment [web:172]
- Calinski-Harabasz Index evaluation [web:170]
- Cluster profiling and interpretation [web:171]

### 5. Business Insights & Strategy
- Customer segment characterization [web:169]
- Targeted marketing recommendations per cluster [web:171]
- Risk management strategies [web:170]

## 📊 Expected Customer Segments

Typical clusters identified in credit score analysis [web:169][web:171]:

- **High-Value Customers**: High credit limits, frequent purchases, consistent high payments
- **Regular Users/Transactors**: Moderate spending, reliable payment patterns, pay in full
- **Inactive Users/Revolvers**: Low activity, carry balances, minimum payments
- **High-Risk Customers**: Frequent cash advances, payment delays, high debt-to-income ratio

## 🔍 Key Features Analyzed

- Credit Score
- Credit Limit
- Balance
- Purchase Patterns (installments, one-time, cash advances) [web:169]
- Payment History
- Debt-to-Income Ratio [web:170]
- Customer Tenure
- Credit Utilization Rate [web:170]

## 📈 Business Applications

- **Marketing Personalization**: Tailored campaigns for each customer segment [web:166]
- **Risk Management**: Identify high-risk customers early [web:170]
- **Product Optimization**: Match credit products to customer profiles





