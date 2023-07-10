# Telecom-Churn-case-study-by-Sheetal--Viren--Mohan
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
For many incumbent operators, retaining high profitable customers is the number one business goal.
 
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
In this project, we will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
 After identifying important predictors, display them visually – we will use plots, summary tables etc. - whatever you think best conveys the importance of features.
recommend strategies to manage customer churn based on your observations.
The provided Telecom dataset has around 9000 data points. This dataset consists of various attributes such as Churn, Age on Net,average revenue per user , service packs, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not.

The target variable, in this case study, is the column ‘Churn’ which tells whether customer will leave this network.
Steps followed
Reading, understanding and visualising the data
Preparing the data for modelling
Building & Evaluating the model
So we evaluate various model like PCA , Logistic regression, Decision tree, Ada Boosting, Random forest and finally suggest which is the best model.
###Conclusion We ran the following models and have summarized our findings in the table below -

Princple component Analysis and Regression

Logistic Regression with RFE and VIF

Decision Tree

ADA Boosting with Decision Tree

Random Forest

Methodology Test - Precision Test - Recall

--PCA with regression 37 71.33 
--Logistic Regression 40.7 71.33 
--Decision Tree 73 46 
--ADA Boosting with DT 69.1 52.3 
--Random Forests 73 49.0 

We see that almost on all models the values are coming very similar to each other and more often than not there is a trade off between precision and recall Since both the metrics are important, we feel that going ahead with Random forests
