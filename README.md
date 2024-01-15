
# Lending Club Case Study

This repository contains a case study on loan data analysis. The case study includes exploratory data analysis (EDA) and visualizations to understand the relationships between various loan attributes and the loan status. Basic understanding of risk analytics in banking and financial services and to understand how data is used to minimise the risk of losing money while lending to customers.

## Table of Contents

* General Information
* Technologies Used
* Analysis
* Visualizations 
* Conclusions
  


## General Information

# Background

We assume we work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

*. If the applicant is likely to pay the loan, not approving such loan will result in loss for the company 
*. If the applicant is likely to default the loan, approving such loan application will also result in loss.

The source data loan.csv contains the information about past loan applicants and whether they ‘defaulted’ or not. We need to perform EDA to understand how consumer attributes and loan attributes infulence the decisioning. In other words, the company wants to understand the driving factors behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

*.Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
   * Fully paid: Applicant has fully paid the loan (the principal and the interest rate).
   * Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
   * Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
    
*.Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no                    transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

# Business Problem
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.


## Technologies Used

Python Libraries:
* pandas
* numpy
* seaborn
* matplotlib.pyplot


## Analysis

The analysis covers the following aspects:
* Understanding of the given Data
* Data Preparation(Cleaning, Standardisation, treating outliers)
* Data Analysis(Univariate and Bivariate analysis)



## Visualizations

The visualizations include count plots, box plots, bar plots and more to illustrate the relationships between different loan attributes.


## Conclusion

In general, from the given data the applicants with higher loan amount, higher interest rate and higher 
instalment are more likely to default. From our analysis we have identified strong indicators that contributes 
for the loan charge off, by implementing the recommendation we can reduce the risk of default


## Authors:

1. Antony John Sundar Aruldos
2. Subhrabindu Khuntia

    
## Reference Material

1. UpGrad Material – Live session and recordings
2. Seaborn Libraries 
    https://seaborn.pydata.org/tutorial/categorical.html
    https://seaborn.pydata.org/tutorial/distributions.html
3. Lending Club website
    https://www.lendingclub.com/personal-loan/rates-fees
    https://www.lendingclub.com/resource-center



