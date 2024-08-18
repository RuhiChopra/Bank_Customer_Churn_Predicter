# Customer Churn Prediction

## Project Overview

The **Customer Churn Prediction** project aims to analyze various demographic and financial attributes of bank customers to predict whether they are likely to leave the bank. Understanding customer churn is crucial for banks as it affects profitability and customer retention. By predicting churn accurately, the bank can implement targeted strategies to retain valuable customers and enhance overall customer satisfaction.

## Dataset

The dataset used in this project is sourced from Kaggle and includes:

- **Number of Rows**: 10,000
- **Number of Columns**: 14

The dataset's goal is to predict customer churn based on their demographic and financial details. The dataset features include:

- **Credit Score**: Customer's credit score.
- **Country**: The country where the customer resides.
- **Age**: The customer's age.
- **Tenure**: The number of years the customer has been with the bank.
- **Balance**: The customer's bank balance.
- **NumOfProducts**: The number of bank products the customer is using.
- **HasCrCard**: Indicates whether the customer holds a credit card (1 for Yes, 0 for No).
- **IsActiveMember**: Indicates whether the customer is an active member (1 for Yes, 0 for No).
- **EstimatedSalary**: The customer's estimated annual salary in dollars.
- **Exited**: Target variable indicating if the customer exited (1 for Yes, 0 for No).

## Data Dictionary

| Column Name       | Description                                                                                       |
|-------------------|---------------------------------------------------------------------------------------------------|
| RowNumber         | Row number                                                                                      |
| CustomerId        | Unique identifier for each customer                                                               |
| Surname           | Customer's last name                                                                           |
| CreditScore       | Credit score of the customer                                                                    |
| Geography         | Country of the customer                                                                         |
| Age               | Age of the customer                                                                            |
| Tenure            | Number of years the customer has been with the bank                                               |
| Balance           | Bank balance of the customer                                                                    |
| NumOfProducts     | Number of bank products the customer is utilizing                                                |
| HasCrCard         | Binary flag indicating whether the customer holds a credit card (1 for Yes, 0 for No)             |
| IsActiveMember    | Binary flag indicating whether the customer is an active member (1 for Yes, 0 for No)             |
| EstimatedSalary   | Estimated annual salary of the customer in dollars                                               |
| Exited            | Target variable indicating if the customer exited (1 for Yes, 0 for No)                              |

## Objectives

The project aims to:

1. **Develop a Predictive Model**: Create a model that can accurately predict customer churn.
2. **Implement Retention Strategies**: Identify high-risk customers to allow for targeted retention efforts.
3. **Improve Business Performance**: Enhance customer loyalty and reduce churn through data-driven strategies.

