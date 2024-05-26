# Logistic Regression for Banking Solutions
## Instructions
### Banking Marketing Campaign
### Business Insight

Long-term deposits allow banks to hold money for a specific period of time, allowing the bank to use that money to enhance its investments. Marketing campaigns for this product are based on phone calls. If a user is not available at a given time, then they will be called back at another time.

### Description of the problem

The Portuguese bank is experiencing a decline in revenue, so they want to be able to identify existing customers who are more likely to take out a long-term deposit. This will allow the bank to focus their marketing efforts on those customers and avoid wasting money and time on customers who are unlikely to sign up.

To address this problem we will create a ranking algorithm to help predict whether or not a customer will sign up for a long-term deposit.

#### Step 1: Data collection
The dataset can be found in this project folder under the name bank-marketing-campaign-data.csv, and you can load it into the code directly from this link:

https://raw.githubusercontent.com/4GeeksAcademy/logistic-regression-project-tutorial/main/bank-marketing-campaign-data.csv
Or download it, and add it by hand in your repository. In this dataset, you will find the following variables:

age. Age of customer (numeric)
job. Type of job (categorical)
marital. Marital status (categorical)
education. Level of education (categorical)
default. Do you currently have credit (categorical)
housing. Do you have a housing loan (categorical)
loan. Do you have a personal loan? (categorical)
contact. Type of contact communication (categorical)
month. Last month in which you have been contacted (categorical)
day_of_week. Last day on which you have been contacted (categorical)
duration. Duration of previous contact in seconds (numeric)
campaign. Number of contacts made during this campaign to the customer (numeric)
pdays. Number of days that elapsed since the last campaign until the customer was contacted (numeric)
previous. Number of contacts made during the previous campaign to the customer (numeric)
poutcome. Result of the previous marketing campaign (categorical)
emp.var.rate. Employment variation rate. Quarterly indicator (numeric)
cons.price.idx. Consumer price index. Monthly indicator (numeric)
cons.conf.idx. Consumer confidence index. Monthly indicator (numeric)
euribor3m. EURIBOR 3-month rate. Daily indicator (numeric)
nr.employed. Number of employees. Quarterly indicator (numeric)
y. TARGET. Whether the customer takes out a long-term deposit or not (categorical)
#### Step 2: Exploration and data cleaning
This second step is vital to ensure that we keep the variables that are strictly necessary and eliminate those that are not relevant or do not provide information. Use the example Notebook we worked on and adapt it to this use case.

Be sure to conveniently divide the data set into train and test as we have seen in previous lessons.

#### Step 3 & 4: Analysis of univariate variables & Analysis of multivariate variables
Analysis of diferent variables with graphical representation for a better understanding of the data set

#### Step 5 : Feature engineering & Outliers
Outlier Analysis: Identifying data points that deviate significantly from the majority using statistical methods, z-scores, or machine learning techniques, and addressing them by removing, transforming, or adjusting to enhance model robustness and accuracy.
Feature Engineering: Developing new features through scaling, encoding, and polynomial expansion, and selecting the most relevant ones to enhance predictive power and improve model performance while reducing dimensionality.

#### Step 6 : Feature selection
Feature Selection: Identifying and choosing the most relevant features to improve model performance, reduce dimensionality, and enhance computational efficiency.

#### Step 7:Logistic Regression model
save up the clean and ready to deploy model





