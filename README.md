# Bank-Credit-Card-Churn
Dataset: https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?select=BankChurners.csv

Powerpoint: https://docs.google.com/presentation/d/1weR2H_uZYBXF6U1A0S4KW7Wy5G4a19S5fxm8heeyy74/edit?usp=sharing


Business Problem:
To predict which customers are likely to close a bank's credit card (churn) based on their activity and characteristics, so the bank can proactively offer them better services or benefits to retain them.

Why: 
Interest rates are the primary source of income for financial institutions. Credit Cards and Mortgages are among the most common products that generate revenue for a bank. For this reason, banks would like to minimize the amount of consumers who close their accounts. 
Overview and Approach

The Kaggle dataset to do EDA on and discover trends. Areas to check are bank account activity, credit limits and demographics. The dataset had 10K lines of information on customers however it was heavily imbalanced with the majority of customers being existing and the remaining smaller amount being the churn customers. This means that code and modeling techniques would need to be able to manage the imbalance and still produce a high success rate in accuracy. 
EDA
Biggest takeaway was related to inactivity and potential dissatisfaction from consumers. Some of the main factors in the data showed how long customer went with inactivity on their accounts as well as how many time customers called in for support. These were also among the higher feature importance in the prediction models that were used to determine which customer would churn. 

Conclusion
A consumer provided with a low credit limit will most likely not be happy with their card and ultimately not use it. This would be proven from how much of their balance is left available to spend or low average utilization. Using grid search and SMOTE techniques the Random Forest model had the best results in determining the accuracy of consumers who would churn with an overall score of 93%. 
