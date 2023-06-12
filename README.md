# python-prosper-loan

Introduction:
The Prosper Loan dataset provides a wealth of information regarding loans facilitated through the Prosper platform. The dataset includes attributes such as loan amount, interest rate, borrower income, loan status, credit score, and many other variables. By analyzing this dataset, we can gain valuable insights into loan performance and borrower behavior.

DATA EXPLORATION
we will conduct an exploratory data analysis on the dataset. We will use Python and data visualization libraries to explore the dataset’s variables and understand the data’s structure, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships.

Data Quality Check:
Before conducting the analysis, we performed a thorough data quality check to ensure data integrity and consistency. This process involved identifying and handling missing values, removing duplicates, and addressing any inconsistencies in the dataset.

Data cleaning:
1. choose subset of features important
2. drop duplicated rows based on listing number
3. convert datatypes of TotalTrades and TotalInquiries to int , ListingCreationDate to datetime
4. fill in missing values of occupation and DebtToIncomeRatio
5. change listing category numeric to string.
6. change all columns to lower case for easy coding navigations so as to avoid errors
7.remove irrelivant rows and columns that are not beneficial to the analysis so as to have a consistent data, for move defined result

Insights:
January has the highest number of loans listed as expected from starting of new year , whereas april sees the least number of loans listed. There is an upward trend in loans listed with each passing year

The distribution of APR looks multimodal. A small peak centered at 0.1, a large peak centered at 0.2. There is also a small peak centered 0.3. Additionally, there is a very shape peak between 0.35 and 0.36. Only very few loans have APR greater than 0.43.

Distribution has unimodal peak around 0.2 with unusual peak around 0.25 which indicates most people prefer 1:4 ratio of debt to Income which is a good thing.

At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. Overall, the borrower APR decrease with increase of loan amount

The borrower APR decreases with the increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR.

The borrower APR changes with the occupation,Interestingly with student in technical schools having least and college sophomores having highest average rating.

Interestingly, the borrower APR decrease with the increase of borrow term for people with HR-C raings. But for people with B-AA ratings, the APR increase with the increase of borrow term.
