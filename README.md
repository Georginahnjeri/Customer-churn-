# CUSTOMER CHURN PREDICTION
I am building a model to predict customer churn 


---
## Introduction
 
### In today's world of machine learning, most companies build classification models to perform churn analysis on their customers.We have been tasked to create a prediction model for a telecommunication company to help predict id a customer will churn or not. We are to also help them uderstand their data and know what factors affect the rate at which customers stop using their network to understand their data.

---



###  Data Collection
### In this step, I will describe my data collection process.
### 3 datasets were provided for this project.
### I loaded the first dataset of 3000 records from a database I accessed remotely.
SERVER_NAME=dap-projects-database.database.windows.net
USER=LP2_project
PASSWORD=Stat$AndD@t@Rul3
DATABASE_NAME=dapDB
TABLE_NAME=dbo.LP2_Telco_churn_first_3000

### To load the second data, I downloaded it from a github repository in a file called LP2_Telco_Churn-second=2000.csv.
### Here is the github repository  https://github.com/Azubi-Africa/Career_Accelerator_LP2-Classifcation/tree/main

### To load the third data, which is my testing data, I downoaded it from a one drive in a file named Telco-churn-last-2000.xlsx
### Here is the one drive link https://azubiafrica-my.sharepoint.com/personal/teachops_azubiafrica_org/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fteachops%5Fazubiafrica%5Forg%2FDocuments%2FCareer%20Accelerator%20Data%5FSets%2FLP2%20Datasets&ga=1

---

###  Data Preparation
### I will explain the data preprocessing steps.
### Handling missing values
### To do this,I first converted boolean columns to object Dtypes, true with yes, and false with no.
### There was on emissing value i the churn colunm, i dropped it
### I then replaced the remaining missing values with the mode of their respective columns
### I then converted the Dtype of senior citizen to object


### EDA 
### I performed summary statistics of the data, Univariate, univariate  and multivariate analysis

### I then answered these analytical questions I had written down
    1.What is the total churn rate?
    2.How does the different boolean attributes affect the churn?
    3.How does the different non-boolean attributes affect the churn?
    4.How does the different numerical attributes affect the churn?
    5. How does tenure affect the churn?
    6.How does the type of internet service affect churn?
    7.How does the type of contract affect the churn?
    8.How does the type of payment method affect the churn?

 ### Hypothesis testing
 ### I performed the hypothesis testing and these were the results. T-statistic: 14.63042633194232
P-value: 1.678344901798023e-47
Reject null hypothesis: There is a significant difference in average monthly charges between churners and non-churners.  

### I then looked at correlation between numeric values and target variable and plotted a correlation matrix
---
### Data preparation

### Feature processing
### I checked the feature dependency on the target variable using mutual information score:a measure of the mutual dependence between two random variables. In the context of machine learning and feature selection, mutual information score quantifies the amount of information obtained about one random variable through the other random variable.
### I then created bins for Tenure column to reduce data complexity and potentialy increase our model performance
### Next, I dropped the  original tenure column

Addressing data inconsistencies: Resolving inconsistencies, errors, or discrepancies in the data.
Handling data skewness: Addressing class imbalance Standardizing or normalizing numerical features, converting categorical variables into numerical representations (e.g., one-hot encoding), and dealing with outliersissues if present in the dataset.


---

### I then created a power BI dashboard visualizing my analytical questions.

---

## Additional Information
Note that this project is for educational and research puprose only.Any insights and predictions should be interpreted with caution in real world applications

---