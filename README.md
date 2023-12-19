
# Jaza Telecom Company Customer Churn Prediction Model

![Customer Churning](https://editor.analyticsvidhya.com/uploads/17047What-stops-customer-churn-Having-a-centralized-data-hub-does-and-heres-why.jpeg)

## Overview

Customers represent the cornerstone of success for telecom companies. If these customers decide to switch providers due to factors such as high fees, superior offers from competitors, unsatisfactory customer service, or other unidentified reasons, it becomes an indirect measure of the telecom company's performance. Therefore, in the context of telecom companies, monitoring customer churn becomes especially vital as it serves as a key metric for evaluating their effectiveness and competitiveness in the market.

## Business and Data Understanding
#### Stakeholder Audience:
The primary stakeholder for this project is Jaza Telecom Company, a telecommunications company. The focus is on addressing the business problem of customer churn. The key stakeholders include executives, marketing teams, and customer service teams within Jaza Telecom. Executives are interested in improving overall company performance and profitability, while the marketing and customer service teams are concerned with customer acquisition and retention strategies.

#### Business Problem:
The company aims to shift its strategy by recognizing the importance of customer retention. The objective is to leverage insights from past experiences, develop a machine learning model for predicting customer churn, and ultimately increase customer retention rates by at least 5%. This aligns with the findings from Bain & Company, which suggest that a modest increase in retention rates can lead to significant profit boosts.

#### Dataset Choice:
The dataset used for this analysis is sourced from https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset and includes various features related to customer interactions, such as account length, international plan status, voice mail plan status, call statistics (e.g., day minutes, evening minutes, night minutes), and customer service calls. The dataset also contains a binary indicator for churn.

#### Dataset Overview:
The dataset consists of 3333 entries and 21 columns.
Columns include customer information (e.g., state, account length, phone number), service details (e.g., international plan, voice mail plan), and usage metrics (e.g., total day minutes, total night minutes).
The target variable is 'churn,' indicating whether a customer has discontinued services (binary: True or False).

## Modelling
Three machine learning models were employed to predict customer churn for Jaza Telecom Company: 
-  Simple model - Logistic regression
-  Complex Model- Random forest
-  Hyperparameter tuned for Random forest model

## Model Evalution
Logistic Regression Results:
-  Logistic Regression achieved an accuracy of 92%, with a balanced precision and recall for both churn and non-churn classes.
-  The confusion matrix and classification report highlighted the model's ability to minimize both false positives and false negatives.

Random Forest Results:
-  Random Forest demonstrated superior performance with an accuracy of 96%.
-  The confusion matrix revealed a low number of false positives and false negatives, indicating a balanced predictive capability.
-  The ROC curve, with an AUC of 0.99, demonstrated the model's strong discriminatory power.

Hyperparameter Tuning:
-  Hyperparameter tuning was performed on the Random Forest model using GridSearchCV to find the optimal set of parameters.
-  The hyperparameter-tuned Random Forest model maintained a high accuracy of 96%, with further improvements in false positives and false negatives.

## Conclusion
The machine learning models, particularly the hyperparameter-tuned Random Forest, proved effective in predicting customer churn for Jaza Telecom. The Logistic Regression model, although simpler, still provided a respectable accuracy of 92%. However, the Random Forest model's enhanced complexity led to a significant accuracy improvement of 96%.

The hyperparameter-tuned Random Forest, with its optimized parameters, demonstrated robust performance with minimized false positives and false negatives. This makes it a valuable tool for Jaza Telecom in identifying and retaining customers at risk of churning. The models, along with their evaluations, can be utilized for informed decision-making, allowing Jaza Telecom to implement targeted retention strategies and potentially increase profitability.


