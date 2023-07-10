# Telco_Churn_Feature_Engineering

## Business Problem

A machine learning model is requested to predict customers who are likely to churn (leave) the company. Prior to developing the model, it is expected to perform data analysis and feature engineering steps.

![1_WqId29D5dN_8DhiYQcHa2w](https://github.com/sametaydn/Telco_Churn_Feature_Engineering/assets/53154449/d16c26a1-e48b-4c06-92cb-df4f34934a19)

## Dataset Story

The dataset for Telco customer churn contains information about a fictional telecommunications company that provides home phone and internet services to 7043 customers in California during the third quarter. The dataset includes details on which customers have churned (left) the services, which customers have stayed, and which customers have enrolled in the services.

| Column            | Description                                                                |
|-------------------|----------------------------------------------------------------------------|
| CustomerId        | Customer ID                                                                |
| Gender            | Gender                                                                     |
| SeniorCitizen     | Whether the customer is a senior citizen (1 for yes, 0 for no)             |
| Partner           | Whether the customer has a partner (Yes or No)                              |
| Dependents        | Whether the customer has dependents (Yes or No)                             |
| Tenure            | Number of months the customer has stayed with the company                   |
| PhoneService      | Whether the customer has phone service (Yes or No)                          |
| MultipleLines     | Whether the customer has multiple lines (Yes, No, or No phone service)      |
| InternetService   | Internet service provider for the customer (DSL, Fiber optic, or No)        |
| OnlineSecurity    | Whether the customer has online security (Yes, No, or No internet service)  |
| OnlineBackup      | Whether the customer has online backup (Yes, No, or No internet service)    |
| DeviceProtection  | Whether the customer has device protection (Yes, No, or No internet service)|
| TechSupport       | Whether the customer has tech support (Yes, No, or No internet service)     |
| StreamingTV       | Whether the customer has streaming TV (Yes, No, or No internet service)     |
| StreamingMovies   | Whether the customer has streaming movies (Yes, No, or No internet service) |
| Contract          | Contract term of the customer (Month-to-month, One year, Two year)          |
| PaperlessBilling  | Whether the customer has paperless billing (Yes or No)                      |
| PaymentMethod     | Payment method of the customer (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) |
| MonthlyCharges    | Monthly charges billed to the customer                                     |
| TotalCharges      | Total charges billed to the customer                                       |
| Churn             | Whether the customer has churned (Yes or No)                                |

## Process
* Developed a model that can predict customers who will leave the company.
* This project includes Feature Engineering, Encoding Operations such as One-Hot Encoder, Standardization, and Modeling.
