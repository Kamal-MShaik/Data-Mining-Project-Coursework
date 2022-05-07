# Retention of credit card customers
# **1.0 Introduction**
Customer retention is a vital problem in every company. Every client retention is an essential indicator that reveals the reality about overall customer retention rates. A thorough examination of existing models for forecasting customer retention is conducted in this project, and four models based on Machine Learning algorithms is proposed for predicting customer turnover in the banking industry. The suggested machine learning process combines methods such as kNN, Decision Tree, SVM, and Random Forest. The performance measures that were examined between these models built were accuracy, precision, recall, and F1 score. The Random-Forest Classifer model has been found to perform better than other models.

Almost every service provider has introduced modern technologies that help them to provide clients with simple ways to save money or do transactions. The customer retention process is handled by the company’s customer relationship management department consisting of data scientists and analysts. As a result, the executive officers’ choice to adjust the operations or expand their services in order to keep current consumers or attract new ones is important.

Banks employ analysts to create reports based on client data in order to keep track of their customers. Data on both current and defaulting customers will often include transaction details, services customers are actively utilizing, personal information such as family details, employment, and income, and credit records. Data analysts deal with the data by applying algorithms, creating predictions, and generating reports that show the bank’s customers’ operations. These insights are vital in making decisions for effective retention-related outcomes.

This project analyzes the data and predicts whether a client will retain or not based on a variety of parameters.

# **2.0	Data description**

The dataset for this project is sourced from Kaggle website. Link for the data is provided below:
https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?taskId=2729 

The dataset contains information on 10128 customers with 21 attributes with no null values in any record, they are divided into two groups: those who exit (represented by 1 in the target variable) and those who did not leave (represented by 0 in the target variable). The dataset includes 1627 clients who left the bank services, with the remainder remaining. Individual client data include annual income, marital status, gender, age, utilization period, opening balance, number of dependents, values indicating if the customer has a credit card and card category, values indicating whether the customer is an active member, and fnally the customer’s credit balance.

# **3.0	Task description**

<img width="287" alt="flow" src="https://user-images.githubusercontent.com/90293681/167235769-485c674c-3d4a-4cbe-9bde-751384f45f15.png">

Four models were applied to fit the data in this research. GridSearchCV from Sklearn was used to discover the optimum parameters, model, and scores. GridSearchCV makes use of a user-defined set of hyperparameters. The model is well trained using the training data using these parameter combinations

### **please refer to attatched ipynb file or code PDF and Report pdf for a detailed view of experimentation and results**
