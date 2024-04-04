# credit_risk_classification

# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

ANSWER: The purpose of the analysis was to see evaluate the loan_status of creditors. The goal of using the model was see if individals have more of an healthy loan or high risk loan. So a Logistic Regression model was used to predict if creditors had a healthy loan or high risk loan status. The variables I tried to predict for this challenge was the loan_status. If the values were 0 ("healthy loan status") and if the value was 1 ("high risk loan status"). The financial data within this dataframe includes the loan_size, borrower_income and the total_debt. The loan_status can be compared to the total_debt because if the model predicts a healthy loan status that can mean that the creditor does not have a lot of debt. I used a Logistic Regression to predict the loan_status variables. Using supervised machine learning, the columns were divided between X and y variables to test the logistic regression. Using a train_test_split the variables were determined between predictions and actuals. Based on these two new tests, a classification report and confusion matrix was developed to test the accuracy of the predictions model. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    
ANSWER: *The accuarcy score is about 90%. The precision score is 85%. The Recall score is approximately 91%. Since the accuracy score is 90% that means that the model is doing well in close observations but the model is not 100% accurate. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

ANSWER: From the machine learning models the model that would prehaps perform best in this instance seems to be a linear regression model. The linear regression model looks at the best predictions from the comparision between positive observed values and has a line of best fit. The logistic regression model can help predict outcomes from the data and find the threshold but the results are not completely accurate. The logistic regression model predicts categorical data and the linear regression model predicts continuous data. Continuous data is better as these predictions would benefit in determining possible outcomes of the future. A linear regression would probably be closer in prediciting the trends in the data, with better accuracy and precision values. The performance of the model does depend on the problem we are trying to solve. The type of predictions we are trying to make may require a type of model that best fits the response variable. The performance of model depends mainly on the type of datasets, for instance the size, completeness and structure of the data. 

If you do not recommend any of the models, please justify your reasoning.

*Had help from a program tutor and referred to class materials. 


