# Customers Churn Value classification project
Try the [Churn prediction app here]((https://churnprediction.streamlit.app))!

This repo contains a python notebook file that can be opened in Jupiter Notebook or for example in Google Collaboratory.
### What is Churn?
Churn is the measure of how many customers stop using a product.
It would be nice to learn how to identify those customers who may leave your service. In this case, we will be able to build processes in such a way as to retain these customers.
By analyzing churn, we can understand the features of the product that provide the most value for our customers. And to concentrate efforts on these parts of the product.
We can also use churn data to understand the demand for our product among different segments of potential customers.

### Goal:
To understand which factors influence on customers' churn value. To define which segments of customers choose rather to churn or to stay.

### Data:
The Telco customer churn data contains information about a fictional company that provided phone and Internet services to 7043 customers in California in Q3. It indicates which customers have left, stayed, or signed up for their service. The data set is separated to several files with information about:
* Demographics: include gender, dependents, family status, etc.,
* Churn Data: indicates whether or not the customer left within the last month,
* Information about the types of services each customer has, monthly and total charges.


Source: https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113
### Process:
* The data-set was created by merging several files and selecting columns.
* Outliers and missing values check.
* Exploratory Data Analysis.
* Categorical Values Encoding.
* Feature Engineering.
* Customer Segments Analysis.
* Models trained and evaluated:
  * Logistic Regression,
  * Decision Tree Model,
  * Random Forest,
  * Boosted Trees:
    * Gradient Boosting,
    * XGBoost.
  * Validation with the StratifiedKFold.
  * Features Importance.
* Conclusions.

### Important!!! 
All files should be located in the same folder.
We recommend you to download the whole folder instead of separate files. Don't change names of folders and files.

### Files with data: 
* Telco_customer_churn_demographics.xlsx
* Telco_customer_churn_status.xlsx
* Telco_customer_churn_services.xlsx

### Libraries: 
* matplotlib==3.7.1
* numpy==1.22.4
* pandas==1.5.3
* scikit-learn==1.2.2
* scipy==1.10.1
* seaborn==0.12.2
* statsmodels==0.13.5
* xgboost==1.7.5

