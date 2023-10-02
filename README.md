# Lending Club Case Study
> The case study aims to predict which applicants have the maximum probability of defaulting while repaying back a loan


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project is about analyzing a loan dataset for a consumer lending company which wants to decide whether to give a loan to an applicant or not
- As part of case study we are analyzing applicants which have status charged off, we analyze these applicants on the basis of various parameters such as annual income, loan amount, term etc.
- Business problem we are trying to solve is how to predict or better reduce financial loss by giving a loan to a person who is not likely to repay the loan
- The dataset is a loan dataset which consists of various data such as Term of loan, house ownership, verification status etc

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- People with more than 10 years of experience (employee length 10+ years)
- People with 3 years of term
- People with Grade B
- People with house ownership as RENT or Mortgage
- People without verification
- People with 6k-8k of loan amount
- People with rate of interest between 11 to 13
- People with year of issue 2011 or month of issue December
- With an increase in funded_amnt_inv the loan amount decreases
- With an increase in funded_amnt_inv number of installments also increases
- The number of installments increases with the increase in loan amount
- For home ownership for MORTGAGE for annual_inc in year 2008
- For home ownership for MORTGAGE for loan_amnt in year 2011
- For home ownership for OTHER for loan_amnt in year 2011
- For home ownership for MORTGAGE funded_amnt_inv, installment, int_rate, loan_amnt, revol_utils increased rapidly every year. So increase in any of these columns will directly impact others and will have more changes to be defaulted
- For Home ownership MORTAGE for verified and for source verified for annual income
- For home ownership OTHER for verified and source verified for annual income
- For medical purpose for loan status fully paid for loan_amnt in year 2007
- For Major Purchas for status charged off for loan_amnt in 2007
- With every issue_year funded_amnt_inv, int_rate and installment increases
- The loan amount was common in most of the year, it increases by approximately 5k in 2011

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python Version 3.11.x
- Pandas
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Upgrad Live session
- https://www.youtube.com/watch?v=BVmL3VQCmEM
- https://youtu.be/fiQhxn9RjEQ?si=BCJXn_9PzShUvkNj 



## Contact
Created by [@mohsin-tariq] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->