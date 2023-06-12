# python-prosper-loan

Introduction:
The Prosper Loan dataset provides a wealth of information regarding loans facilitated through the Prosper platform. The dataset includes attributes such as loan amount, interest rate, borrower income, loan status, credit score, and many other variables. By analyzing this dataset, we can gain valuable insights into loan performance and borrower behavior.

DATA EXPLORATION
we will conduct an exploratory data analysis on the dataset. We will use Python and data visualization libraries to explore the dataset’s variables and understand the data’s structure, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships.

Data Quality Check:
Before conducting the analysis, we performed a thorough data quality check to ensure data integrity and consistency. This process involved identifying and handling missing values, removing duplicates, and addressing any inconsistencies in the dataset.

DATA CLEANING:
1. choose subset of features important
2. drop duplicated rows based on listing number
3. convert datatypes of TotalTrades and TotalInquiries to int , ListingCreationDate to datetime
4. fill in missing values of occupation and DebtToIncomeRatio
5. change listing category numeric to string.
6. change all columns to lower case for easy coding navigations so as to avoid errors
7.remove irrelivant rows and columns that are not beneficial to the analysis so as to have a consistent data, for move defined result
