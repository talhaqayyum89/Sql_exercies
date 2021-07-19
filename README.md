# Sql Exercise 
Howdy!

The main goal of this exercise is to test your data wrangling skills and data extraction abilities. This exercise shouldn't take more than 1-2 hours to complete. We encourage you to submit your solution even if you are not able to complete the exercise in given time. Please upload your solution on a code sharing tool such as github, gitlab or bitbucket.

# Exercise
## Introduction

Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default.

The data for this exercise is available in the data/ folder.

The file data.csv in the data/ folder contains the information of loan as well as the loanee. Following information regarding the loan and loanee are provided:

Loanee Information (Demographic data like age, income, Identity proof etc.)
Loan Information (Disbursal details, amount, EMI, loan to value ratio etc.)
Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.)
The details of the numerous fields in the csv file are explained in the microsoft word file: Data Dictionary.xlsx in data/ folder

# Expectations

There is a field LOAN_DEFAULT in the data.csv file. This field tells us whether the loanee defaulted his/her loan or not. This is our target variable. We should be able to predict, using the available data, whether the loanee will default his/her loan or not.
Given below are your tasks for this exercise:
1.	First of all, you will identify fields with more than 50% null data. These fields should be removed from analysis.
2.	Write SQL query to fetch unique ids having a disbursed amount greater than or equal to 20000 and less than or equal 70000 with respect to delinquent accounts in past 6 months.
3.	Write SQL query to find 2nd highest disbursed amount when Loan default is 1.
4.	Write SQL query to deduce new field in the data; such as age of the loanee based on the Date of birth.
5.	Find all duplicated rows (if any) and make a new table as _dupicate_data_ having all the duplicate fields.
6.	Find all the customer’s average account age who have primary active accounts more then 1.
7.	Analyze, using SQL queries, whether the demographic data plays a major role in a loanee defaulting his/her loan or the financial data.
8.	Present your recommendations for the estimators that can be used as a model to predict loan defaults.
You are expected to submit solution stating queries against each task. You will be judged on your coding approach, code quality and accuracy of analysis. Feel free to contact us anytime if you have any queries regarding the exercise.

Thank you and Best of luck!

