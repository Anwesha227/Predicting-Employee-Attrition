# Predicting-Employee-Attrition

We will be looking at the data of a large insurance company focused on sales team attrition. Insurance sales teams help insurance companies generate new business by contacting potential customers and selling one or more types of insurance. The department generally sees high attrition and thus staffing becomes a crucial aspect.

The data contains the monthly information for a segment of employees for 2016 and 2017 and we shall try to predict whether a current employee will be leaving the organization in the upcoming two quarters (01 Jan 2018 - 01 July 2018) or not, given:

 - Demographics of the employee (city, age, gender etc.)
 - Tenure information (joining date, Last Date)
 - Historical data regarding the performance of the employee (Quarterly rating, Monthly business acquired, designation, salary)
 
 
 ### Broad overview of how this case study is organized :
 
 We will perform the usual exploratory data analysis steps and also engineer some relevant features. Then we shall look at a simple decision tree classifier, followed by ensemble models such as Gradient Boosted Decision Trees (using XGBoost) and Random Forest, and use both Grid and Random Search to look for the best hyperparameters. We will look at feature importances, accuracy, precision, recall, F-score, ROC curves and areas under ROC curves for each model. We will then compare our models and summarize our insights and recommendations. 
