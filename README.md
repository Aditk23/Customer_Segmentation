# Customer_Segmentation : Project Overview

## Problem Statement
An automobile company has plans to enter new markets with their existing products (P1, P2, P3, P4 and P5). After intensive market research, they’ve deduced that the behavior of new market is similar to their existing market. 

In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for different segment of customers. This strategy has work exceptionally well for them. They plan to use the same strategy on new markets and have identified 2627 new potential customers. 



## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn  
**Analytics Vidhya Competition Link:** https://datahack.analyticsvidhya.com/contest/janatahack-customer-segmentation/


## Data Cleaning
There were many missing values in the data. Missing values were filled by relating data of missing  columns with other columns. For example missing values for Spending_Score were filled corresponding to customers Family_Size, greater the family size greater spending score. Missing values were present both training and testing data.  


## Model Building 

Firstly,all categorical variables with 2 classes were mapped to 0's and 1's and other categorical variables with more than 2 classes were converted into dummy variables. I tried 3 models first with KNeighborsClassifier second with Random Forest and third model was tuned Random Forest model.


## Model performance
KNeighborsClassifier gave testing accuracy of 93.84%. In case of Random Forest training accuracy was 90.64% while the testing accuracy was 94.48% as per my submission on AnalyticsVidhya.



