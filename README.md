# -Insurance-Claim-Prediction-and-Customer-Segmentation

This project involves two tasks:

Predicting insurance claim status and providing recommendations to the management.
Segmenting customers based on their credit card usage.
## Task 1: Predicting Insurance Claim Status
Problem Description:
An insurance firm offering tour insurance is experiencing high claim frequency. The goal is to build a model that predicts claim status and provides recommendations to the management.

### Data Dictionary:
* Target: Claim Status (Claimed)
* Code of tour firm (Agency_Code)
* Type of tour insurance firms (Type)
* Distribution channel of tour insurance agencies (Channel)
* Name of the tour insurance products (Product)
* Duration of the tour (Duration)
* Destination of the tour (Destination)
* Amount of sales of tour insurance policies (Sales)
* The commission received for the tour insurance firm (Commission)
* Age of the insured (Age)
### Project Steps:
* Data Ingestion: The dataset is read and explored for descriptive statistics, null values, and duplicates.

* Data Analysis: Univariate and bivariate analysis is performed to understand the data better. The analysis includes distribution plots and boxplots for numerical features and count plots for categorical features. Outliers are also examined.

* Data Preprocessing: Data is prepared for modeling. Categorical features are converted to numerical codes.

* Model Building: Three models are built and compared: Decision Tree (CART), Random Forest, and Artificial Neural Network (ANN). GridSearchCV is used for hyperparameter tuning.

* Model Evaluation: Model performance is assessed using accuracy, confusion matrices, classification reports, and ROC-AUC curves for both training and test datasets.

## Task 2: Customer Segmentation Based on Credit Card Usage
### Problem Description:
A leading bank wants to develop customer segmentation to provide promotional offers based on credit card usage.

### Data Dictionary:
* spending: Amount spent by the customer per month (in 1000s)
* advance_payments: Amount paid by the customer in advance by cash (in 100s)
* probability_of_full_payment: Probability of payment done in full by the customer to the bank
* current_balance: Balance amount left in the account to make purchases (in 1000s)
* credit_limit: Limit of the amount on the credit card (in 10000s)
* min_payment_amt: Minimum amount paid by the customer while making payments for purchases made monthly (in 100s)
* max_spent_in_single_shopping: Maximum amount spent in one purchase (in 1000s)
### Project Steps:
* Data Ingestion: The dataset is read and explored for descriptive statistics, null values, and duplicates.

* Data Analysis: Univariate and bivariate analysis is performed using distribution plots and boxplots for numerical features.

* Data Preprocessing: Data is scaled using StandardScaler.

* Hierarchical Clustering: Hierarchical clustering is applied to the scaled data. The optimum number of clusters is determined using a dendrogram.

* K-Means Clustering: K-Means clustering is applied to the scaled data, and the optimum number of clusters is determined using the elbow curve and silhouette score.

* Model Evaluation: The clustering results are evaluated, and the clusters are visualized.

Both tasks provide insights into insurance claim prediction and customer segmentation, helping the respective organizations make data-driven decisions.

Enjoy exploring the insurance data and customer segmentation models!





