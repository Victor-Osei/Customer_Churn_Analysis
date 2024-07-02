# Customer_Churn_Analysis 
Customer churn is a critical issue for businesses, as acquiring new customers is often more costly than retaining existing ones. This project aims to build a machine learning model to predict customer churn, enabling the business to take proactive measures to retain customers and improve overall satisfaction.


## PROJECT TITLE
CHURN PREDICTION AND ANALYSIS : Leveraging Machine Learning for Customer Retention

## OBJECTIVE
- Learn more about classification models and help the client, a telecommunication company, to understand their data.
- Find the lifetime value of each customer. know what factors affect the rate at which customers stop using their network.
- Predict if a customer will churn or not based on the Payment method.

## GOAL
- To develop predictive models that forecast the likelihood of individual customers churning in the future
- Enabling proactive intervention strategies to retain at-risk customers and maximize customer retention

## Data Sources:
The datasets where extracted from three(3) places.

- First dataset - First 3000 records of the dataset was extracted from Microsoft SQL Server
- Second dataset - The second 2000 records of the dataset was downloaded from GitHub Repository
- Third dataset - The third part of the data was downloaded from a OneDrive (Test Data)

## Hypothesis
- H0: Payment methods does not significantly influence customer churn 
- H1: Payment methods significantly influence customer churn

## Conclusion on Hypothesis
The Chi-Square statistic of 433.207 and the extremely small p-value, we have strong evidence to reject the null hypothesis. This means there is a significant association between payment methods and churn. Therefore, we conclude that payment methods significantly influence churn.


## Research Questions
1.	Is there a relationship between Demographic Factors and Churn rate?
How does gender, senior citizenship, and partnership status relate to churn rates? Are there any significant differences in churn between different demographic groups?

2.	Does the type of Internet service relate to the probability of a customer churn?
Which type of internet service recorded the highest customer churn rate?

3.	Does the Tenure type have a relationship with customer Churn?
Is there a correlation between the tenure of a customer and the likelihood of churn? Do longer-tenured customers exhibit different churn behavior compared to newer ones?

4.	Does the Contract Type have a correlation with the customer churn? 
How does the type of contract (month-to-month, one-year, two-year) influence churn rates? Are customers on longer-term contracts less likely to churn?

5.	Payment Method and Churn:
 Does the chosen payment method impact churn behavior? Are customers using certain payment methods more likely to churn than others?

 ## Installation: 
- pyodbc
- python-dotenv
- openpyxl
- imbalanced-learn

## Authors
Team Fiji Members
