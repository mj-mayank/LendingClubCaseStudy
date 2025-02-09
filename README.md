# Lending Club Case Study
The Lending Club dataset involves predicting whether a loan will be fully paid or charged off (defaulted). This is a classic binary classification problem in machine learning. Our goal is to analyze the data and derive actionable insights.
<!-- You can include any other section that is pertinent to your problem -->

## Dataset Details:
In the given dataset, there are 111 columns with total rows as 39717. The data set is from past loan applications which show the status of Default, Current or Fully paid.
We have 2 types of variables:
- One which gives information about the customer behavior while paying the loan.
- Second types of variables are which impact the loan decision for the company like employment length, home ownership, verification status.

## Steps Taken:
The analysis is divided into three main parts:
1. Data cleaning & Preprocessing
2. Exploratory Data Analysis
3. Recommendations

### 1. Data Cleaning and Preprocessing
Below steps were taken for Data cleaning and preprocessing for different columns
- Handle missing values (impute or drop).
- Remove irrelevant columns (e.g., IDs, free-text fields).
- Convert categorical variables into numerical ones

### 2. Exploratory Data Analysis
- Explore distributions of key variables (e.g., loan amount, purpose of loan, interest rate).
- Analyze relationships between variables (e.g., correlation heatmap).
- Visualize target variable distribution (e.g., percentage of fully paid vs. charged off loans).

### 3. Recommendations
Based on Univariate and BIvariate analysis below were the findings:
- The state of NE, NV, SD has highest defaulters. We should be more cautious while approving loans from these state
- Most of the loan applications were for debt consolidation.
- Most of the applications were approved for int rate of 7.5 or 10%
- Most of the applications were from CA state.
- No of applications were more in the later part of the year
- People with Home Ownership as Rent or Mortgage are more prone to get defaulted for the loan
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Based on the analysis conducted across various variables and factors, below are found to be impacting factors for loan default:
1. Address State
2. Home ownership
3. Grades/Sub Grades
4. Purpose of loan and Loan amount

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
