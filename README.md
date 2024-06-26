# Lending Club Case Study
We are tasked with helping the consumer finance company with risk analysis which
will help company decide which applicant is likely to repay the loan and which applicant might default.

## Dataset:
The available original dataset has 39717 unique entries with 111 features. 
dataset shape (36717,111)

## Target Column:
After analysing the dataset we came to know that, **loan_status** will be the target column
its a categorical column with three unique values fully paid, charged-off (defaulted) and current (borrower is still paying and not defaulted yet)


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Performing Exploratory Data Ananlysis on the dataset belonging to the consumer finance company which contains the records of loan provided to the various customers in the past.
- We are trying to identify the features that will help us in knowing which borrowers are likely to default and which are more likely to pay back the loan.
- Dataset belonging to an online loan company conatining records of its past borrowers.

## Technologies Used
- numpy library - version 1.26.4
- pandas library - version 2.1.4
- matplotlib library - version 3.8.0
- seaborn library - version 0.13.2

## Conclusions
- Loans with lower intereset rate have higher chance of getting fully paid.
- Loan with shorter term (36 months) have a higher chance of getting fully paid than a loan for longer term (60 months)
- Majority of loans are taken for debt consolidation and have high rate of getting fully paid. where as nearly 25% of loan taken for small buisnesses get charged-off.
- Borrowers with employment of more than 10 years are more liekly to full pay the loan.
- Loans graded A & B have higher chances of getting fully paid.


## Acknowledgements
- This is our (Harshdeep and Sumit) small project in journey to explore the vast world of data science.
- The dataset and study material are provided by UpGrad
- This project of upgrad program [Case study](https://www.upgrad.com).


## Contact
Created by [@sumitag07 @harshdeep] - feel free to contact me!

