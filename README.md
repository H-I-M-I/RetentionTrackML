# Customer Churn Prediction using Logistic Regression

This project aims to predict customer churn using logistic regression. Customer churn refers to the likelihood of a customer leaving a service, and predicting it can help businesses take preventive actions. The dataset used includes various customer attributes such as tenure, age, income, and service usage.

## Dataset
We will use a telecommunications dataset for predicting customer churn. This is a historical customer dataset where each row represents one customer. The data is relatively easy to understand, and you may uncover insights you can use immediately. Typically it is less expensive to keep customers than acquire new ones, so the focus of this analysis is to predict the customers who will stay with the company. 

This data set provides information to help you predict what behavior will help you to retain customers. You can analyze all relevant customer data and develop focused customer retention programs.

The dataset includes information about:

*   Customers who left within the last month – the column is called Churn
*   Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
*   Customer account information – how long they had been a customer, contract, payment method, paperless billing, monthly charges, and total charges
*   Demographic info about customers – gender, age range, and if they have partners and dependents

## Model Explanation
The program applies logistic regression to classify whether a customer will churn. The steps include:
1. **Data Preprocessing**: Cleaning and transforming data.
2. **Feature Selection**: Choosing relevant variables.
3. **Model Training**: Applying logistic regression using Scikit-Learn.
4. **Evaluation**: Measuring accuracy, precision, recall, and F1-score.

## Results
The model predicts customer churn with reasonable accuracy, helping businesses identify at-risk customers and improve retention strategies.
