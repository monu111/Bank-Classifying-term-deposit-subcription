# Bank-Classifying-term-deposit-subcription
## Objective :
In this project we have to classify that client will accept the term deposit  subscription or reject the term deposit subscription .I performed extensive data analysis on given client dataset and created a model that can predict the term deposit subscription accepted or rejected by the clients.
![1 (2)](https://user-images.githubusercontent.com/29980448/109007386-1146e280-76d2-11eb-8e20-5d59f82fbc46.png)


## data set link :[Download](https://archive.ics.uci.edu/ml/datasets/Bank%2BMarketing)


# Exploratory Data Analysis & Conclusion:

__Client information :__
- From the analysis, the average age of client approx 40 and Minimum: 18 years old and Maximum: approx 95 years old.

- From the analysis, 25.30% people do admin jobs, 22.47% people do blue-collar and  16.37% do technician jobs. 
- From the analysis, 60.52% were married, 28.09% single,  11.20% divorced and 0.19% unknown.Mostly were married.
- From the analysis, approx 29.54% client have university degree ,23.10% clients high school graduated and 0.04% clients illiterate.
- From the analysis, 79.12% credit not in default, 20.87% unknown and 0.01% in default.
- From the analysis, 52.38% client have house loan and 45.21% clients don't have house loan and 2.40% unknown. 
- From the analysis, 82.43% client have personal loan and 15.17% clients don't have personal loan and 2.40% unknown. 
- From the analysis, 63.47% contacted by cellular phone, 36.53% through telephone.
- From the analysis, Most of the clients last time contacted during May month of the year and less  clients during december month.
- From the analysis, Most of the clients last time contacted during Monday and thrusday week of the day.
- From the analysis, the duration of contact from  0 to 4918 second and average duration of contact to cilent was 258.28 second.

- From the analysis, maximum call duration happend during november month on monday.

- From the analysis, Mostly number of contacts performed 1,2,3 & 4 during  campaign(current campagin).

- From the analysis, Mostly 999  days passed by after the client was last contacted from a previous campaign.

- From the analysis, Outcome of the previous marketing campaign  approx 
86% nonexistent, 10.32% failure & 3.33% sucess.
---

__Analysis of term deposit w.r.t. Client Information :__

  - From the analysis, admin & technician job categories  term deposit higher compare to others.

- From the analysis, married & single category term deposit higher comapre to other marital category.

- From the analysis, university.degree clients term deposit was higher.

- From the analysis, the clients those credit not in default have higher term deposit subcription.

- From the analysis, clients those have house-loan also the term deposit subcrption is higher compare to clients those don't have house-loan clients.
- From the analysis, clients those don't have personal-loan also the term deposit subcrption is higher compare to clients those  have personal-loan clients.
- From the analysis, term deposit is higher in may month compare to other months.
- From the analysis, the client term deposit subcription is higher in may month and Most of the subscription happend on  webnesday in may month.
- From the analysis, as the number of contacts are increasing during campaign, lesser the customers are subscribing to the  term deposit.

- From the analysis of __previous campaign :__ Focusing on success and failure, It is evident that if previous contact results in success there are very high chances that in next contact customer will subscribe to term deposit.Another interesting result is that even if the result of previous contact is failure, there is still chance of customer might subscribe to the term deposit.

- From the analysis, only 11.27 % subscribed the term deposit and 88.73% didnot  subscribed  the term deposit and clearly it is imbalaced dataset. we have to handle it to avoid the bais toward the majority of the class.
---
__Modeling:__ I used Logistic Regression, Random Forest, Decision tree, Support Vector Machine, Extra Tree Classifier & Xgboost classifier .Random Forest outperform the others model.So we can use here Random Forest to predict the client subscribed the term deposit or not.















# Working on it.
