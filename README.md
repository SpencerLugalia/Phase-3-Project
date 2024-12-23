# Project Title

SYRIATEL CHURN

## Overview
In order to use classification prediction machine learning modelling approaches to predict the possibility that a client will stop doing business with SyriaTel within a specified time frame, this study looks at a dataset from the telecom company. In the telco sector, this is known as **Churn**.Large marketing expenditures, such as commissions to sales representatives and advertising budgets, are necessary to acquire new clients. Therefore, once those clients are acquired, it becomes essential to keep them. Understanding the traits or attributes of a customer who is likely to "churn" is what drives any telco company. With this knowledge, the business may anticipate issues and create campaigns that specifically target certain clients to deter them from doing business with the company

## Business Understanding
To diversify its portfolio, your organisation is growing into Movie industry. They want to create a new movie studio, but they have no idea what the possible risks associated with the film industry. We are charged with exploring extensive indepth about the work arounds of the film industry and determine which types of films are currently doing the best at the box office. This must lead to actionable insights that when we present to the head of the new 2 Studios Production Inc we can use to help identify what type of films to create.

## Data Understanding and Analysis

The data source is from Kaggle  [Churn data](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset) to access.


Definition of Column Names:

1. **state**: The state in which the customer resides.

2. **account length**: The duration (in months) the customer has had an account with the service provider.

3. **area code**: The area code associated with the customer's phone number.

4. **phone number**: The customer's phone number.

5. **international plan**: A binary indicator (yes/no) of whether the customer has an international calling plan.

6. **voice mail plan**: A binary indicator (yes/no) of whether the customer has a voicemail plan.

7. **number vmail messages**: The total number of voicemail messages received by the customer.

8. **total day minutes**: The total number of minutes the customer spent on daytime calls.

9. **total day calls**: The total number of daytime calls made by the customer.

10. **total day charge**: The total charge for daytime calls made by the customer.

11. **total eve minutes**: The total number of minutes the customer spent on evening calls.

12. **total eve calls**: The total number of evening calls made by the customer.

13. **total eve charge**: The total charge for evening calls made by the customer.

14. **total night minutes**: The total number of minutes the customer spent on nighttime calls.

15. **total night calls**: The total number of nighttime calls made by the customer.

16. **total night charge**: The total charge for nighttime calls made by the customer.

17. **total intl minutes**: The total number of minutes the customer spent on international calls.

18. **total intl calls**: The total number of international calls made by the customer.

19. **total intl charge**: The total charge for international calls made by the customer.

20. **customer service calls**: The total number of calls the customer made to customer service.

21. **churn**: A binary indicator (1/0) representing whether the customer has churned (left the service) or not.

### Data Preprocessing
- Handling Missing Values: Missing values were identified and imputed using mean/mode techniques where appropriate.
- Feature Encoding: Categorical variables were encoded using one-hot encoding.
- Feature Scaling: Numerical features were standardized to improve model performance.
- Categorical features relationship vs Churn

### Exploratory Data Analysis
EDA revealed key insights into churn patterns:
- Detecting Outliers: Detect outliers in numerical features, helping visualize data distribution and identify extreme values that could impact analysis or modeling.
![Outliers](https://github.com/SpencerLugalia/Group-2-Project/blob/main/Images/Data%20Head.png)

Multicollinearity of data Removing highly correlated features that may not provide additional useful information for modeling.
![Correlation Matrix](https://github.com/SpencerLugalia/Group-2-Project/blob/main/Images/Data%20Head.png)

Distribution of the numerical features: Analyzing the numerical features distributions
![Distribution of Numerical features](https://github.com/SpencerLugalia/Group-2-Project/blob/main/Images/Data%20Head.png)

## The Model
-Models developed include:
    - Logistic Regression
    - Random Forest
    - Decision Tree

- Evaluation Metrics:
    - Accuracy
    - Precision, Recall, F1-Score
    - ROC-AUC Curve

## Recomendation and proposed customer retention strategies

- Focus on the most impactful features identified above to reduce the complexity of the model and make it more effective and effecient.
- Provide targeted offers and discounts to customers based on their patterns and preferences enhancing retention.
- Analyze customer service interaction to identify common ailing issues to the customers and address each promptly.
- address any issue that may hinder experience enhancement.
