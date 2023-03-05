# Lending Club Case Study 
> You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
-  Two types of risks are associated with the bank’s decision:

    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

```
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
```


## Conclusions

```
Based on the analysis we have come to this conclusion the following variables are the most influencial on the loan_status variable.
```

1. term - More defaults were found for loans with 60 months term than loans with 36 months term.

2. pub_rec_bankruptcies - As the bankruptcy increases the number of defaults also increases. Borrower with 2 bankruptcies have higher defaults.

3. int_rate - As the interest rate increases the defaults also increases.  

4. grade & sub_grade - Loans with higher grade or higher sub_grade have higher defaults. Grade G have more defaults than grade A.

5. purpose - people with small business and renewable energy tend to default more.

6. loan_amnt - As the loan amount increases the number of defaults also increases. 



## Technologies Used
- numpy - version 1.23.5
- pandas - version 1.5.2
- matplotlib - version 3.6.2
- seaborn - version 0.12.2

## Contact
Created by [@ankushgarg11] and [@pulkitgangwar] - feel free to contact us!
