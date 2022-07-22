# Clustering-of-credit-card-users
Implementing clustering algorithms to identify customer segments

## About the dataset
The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

Following is the Data Dictionary for Credit Card dataset :-

CUSTID : Identification of Credit Card holder (Categorical)

BALANCE : Balance amount left in their account to make purchases

BALANCEFREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)

PURCHASES : Amount of purchases made from account

ONEOFFPURCHASES : Maximum purchase amount done in one-go

INSTALLMENTSPURCHASES : Amount of purchase done in installment

CASHADVANCE : Cash in advance given by the user

PURCHASESFREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)

ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)

PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)

CASHADVANCEFREQUENCY : How frequently the cash in advance being paid

CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"

PURCHASESTRX : Numbe of purchase transactions made

CREDITLIMIT : Limit of Credit Card for user

PAYMENTS : Amount of Payment done by user

MINIMUM_PAYMENTS : Minimum amount of payments made by user

PRCFULLPAYMENT : Percent of full payment paid by user

TENURE : Tenure of credit card service for user

## Objective:
The aim of this analysis is to develop a customer segmentation to define marketing strategy. We will implement two or three clustering algorithms and on the basis of error metrics, finally decide which algorithm to choose.

## Conclusion:
Three clustering algorithms were implemented: KMeans, DBScan, and Agglomerative Clustering. 
The DBSCAN algorithm had the highest value of Silhouette Score and lowest David Bouldin Score. We know that for optimal number of clusters, the Silhouette Score is the highest and David Bouldin score is the lowest. Hence, DBSCAN shows the best performance in this clustering problem.

Suggestions for further improvement: The model performance can be improved further by doing feature selection or feature engineering. Other clustering algorithms such as PCA or Hierarchical clustering can also be implemented on this data.
