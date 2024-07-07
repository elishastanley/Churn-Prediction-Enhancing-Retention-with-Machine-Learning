# Churn-Prediction-Enhancing-Retention-with-Machine-Learning
## Enhancing Customer Retention through Churn Prediction: A Machine Learning Approach to Classification Models

![alt text](<images/64f89c9909a64782cd497652_chrun diagram - no background-p-800.png>)

## Introduction

Customer attrition is one of the biggest expenditures of any
organization. Customer churn otherwise known as customer attrition or
customer turnover is the percentage of customers that stopped using your
company\'s product or service within a specified timeframe.\
For instance, if you began the year with 500 customers but later ended
with 480 customers, the percentage of customers that left would be 4%.
If we could figure out why a customer leaves and when they leave with
reasonable accuracy, it would immensely help the organization to
strategize their retention initiatives manifold.

## Problem Statement

In this project, we aim to determine the likelihood of a customer leaving the organization, identify key indicators of churn, and develop retention strategies to mitigate this issue.

## Goal and Objectives

- **Goal:** To reduce customer churn by identifying at-risk customers and implementing effective retention strategies.
- **Objectives:**
  1. Identify the key factors that contribute to customer churn.
  2. Develop a predictive model to forecast customer churn.
  3. Propose actionable strategies to improve customer retention based on insights from the model.

## Stakeholders

- **Internal:**
  - Marketing Team
  - Customer Service Team
  - Product Development Team
  - Senior Management
- **External:**
  - Customers
  - Investors

## Data Understanding

| **Attribute**         | **Description**                                                |
|-----------------------|----------------------------------------------------------------|
| Gender                | Whether the customer is a male or a female                      |
| SeniorCitizen         | Whether a customer is a senior citizen or not                   |
| Partner               | Whether the customer has a partner or not (Yes, No)             |
| Dependents            | Whether the customer has dependents or not (Yes, No)            |
| Tenure                | Number of months the customer has stayed with the company      |
| Phone Service         | Whether the customer has a phone service or not (Yes, No)       |
| MultipleLines         | Whether the customer has multiple lines or not                  |
| InternetService       | Customer's internet service provider (DSL, Fiber Optic, No)    |
| OnlineSecurity        | Whether the customer has online security or not                 |
| OnlineBackup          | Whether the customer has online backup or not                   |
| DeviceProtection      | Whether the customer has device protection or not               |
| TechSupport           | Whether the customer has tech support or not                    |
| StreamingTV           | Whether the customer has streaming TV or not                    |
| StreamingMovies       | Whether the customer has streaming movies or not                |
| Contract              | The contract term of the customer (Month-to-Month, One year, Two year) |
| PaperlessBilling      | Whether the customer has paperless billing or not (Yes, No)    |
| Payment Method        | The customer's payment method (Electronic check, mailed check, Bank transfer(automatic), Credit card(automatic)) |
| MonthlyCharges        | The amount charged to the customer monthly                      |
| TotalCharges          | The total amount charged to the customer                        |
| Churn                 | Whether the customer churned or not (Yes or No)                 |

## Hypothesis

- **Null Hypothesis (H1):**
  - "There is no difference in monthly charges `median` between customers who churn and those who do not churn."
- **Alternative Hypothesis (H1'):**
  - "There is a difference in monthly charges `median` between customers who churn and those who do not churn."
- **Null Hypothesis (H2):**
  - "Customer churn depends on the period of time a customer has been with the company."
- **Alternative Hypothesis (H2'):**
  - "Customer churn does not depend on the period of time the customer has been with the company."

## Analytical Questions

1. What is the churn rate among customers?
2. Does the type of internet service influence customer churn?
3. Does the method of billing affect the likelihood of churn?
4. How do support services (tech support and online security) influence customer satisfaction and retention?
5. Does churn vary significantly across gender and age groups?

## Power BI Dashboard

[Power BI LIVE! Link](https://app.powerbi.com/view?r=eyJrIjoiNzg5Yjc4ZTktYmM5My00NmMxLThiYzYtZjNiNGU2NjA2YjllIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9)
![images/Screenshot 2024-07-07 203540.png](<images/Screenshot 2024-07-07 203540.png>)

## Scope and Constraints

- **Scope:**
  - Analysis of customer data from the past two years.
  - Development and validation of a churn prediction model.
  - Recommendation of retention strategies based on model insights.
- **Constraints:**
  - Availability and quality of data.
  - Time and resource limitations.
  - Potential biases in the data that may affect model accuracy.

## Usage

To run this analysis, follow these steps:

```bash
pip install -r requirements.txt
git clone https://github.com/elishastanley/Churn-Prediction-Enhancing-Retention-with-Machine-Learning.git
cd Churn-Prediction-Enhancing-Retention-with-Machine-Learning
jupyter notebook main.ipynb
```

## Technologies Used
- Python: Programming language used for data analysis and modeling.
- Pandas: For data manipulation and analysis.
- NumPy: For numerical computing.
- Scikit-learn: Machine learning library for model building.
- Matplotlib & Seaborn: Libraries for data visualization.
- Jupyter Notebook: Interactive computing environment used for developing the project.
- Power BI: Business analytics service used for visualizing and sharing insights from the data


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries regarding this project, please contact:

Elisha Stanley - <elishastanley255@gmail.com>

Thank you for visiting this repository, and I hope you find the Machine Learning Project useful!
