# Project Name : Lending Club Case Study

Lending Club, a consumer finance company specializing in offering a variety of loans to customers, as part of this case study we need to use Exloratory Data Analysis to understand different attributes of loan and its applicants and how these attributes can impact the loan recovery and aiming to reduce the loan default rates.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#License)


## General Information

### Problem Statement

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

### Business probem we are trying to solve

Lending Club, a consumer finance company specializing in offering a variety of loans to customers, as part of this case study we need to use Exloratory Data Analysis to understand different attributes of loan and its applicants and how these attributes can impact the loan recovery and aiming to reduce the loan default rates.

Losses happens to these finance company when borrowers fail to repay their loans or default. In other words borrowers labeled as "charged-off" when they failed to repay the loans and contribute significantly for losses of the company.

The primary goal of this case study is to identify the applicants where the loan default cases can be high and avoid it by identifying the valued applicants where company can provide risk free debts.

### Objective

1. Identifying applicants where the loan default can be high, so that the company can avoid giving loans and reduces losses.
2. Understand the applicant and its loan attributes where company can provide loans so that company can make profit through interest earned from this loan so that it can be profitable.

### Steps performed

- 1: Data Analysis
- 2: Data Cleaning and Manipulation
- 3: Univariate Analysis
- 4: Segemented Univariate Analysis
- 5: Bivaraiate Analysis
- 6: Observations

### Dataset we used

- The data set we used to analyze the different attributes of loan and its applicants are provided by IIIT, Bangalore throgh loan.csv file


## Conclusions

- Percentagewise grade B3 to G4 and onwards have very high defaults rates (Assuming >10%
default rate is very high)
- Loan for term of '60 months’ has 25% defaults, thus very high default rate(Assuming >10%
default rate is very high)
- Interest rate of 10% and higher have more than 13% defaults, so very high default rates
- Apparently more chances of defaults across all salary groups if rate of interest is greater than
13.85
- Comparatively, purpose “wedding,major_purchase, credit_card, car, home_improvement” have
lower rates of defaulting ,“vacation,debt_consolidation, moving, other,educational, house” have
medium rates of default and “renewable_energy, small_business” have very higher rates of
default
- For annual_inc 140k-160k , installment>490 then there are more chances of defaulting,for
annual_inc 80k-100k , installment>470 then there are more chances of defaulting,for
annual_inc 60k-80k , installment>430 then there are more chances of defaulting
- For salary groups of 40k-60k apparently more chances of defaults if funded_amnt is greater
than 12000, for salary groups of 60k-80k,80k-100k apparently more chances of failure if
funded_amnt is greater than 15000, for salagy group of 120k-140k apparently more chances
of failure if funded_amnt is greater than 16275, for salary group of 140k-160k apparently
more chances of failure if funded_amnt is greater than 16500
- No significant difference in percentages of defaults for every emp_length 
category
- home_ownership category 'Other’ have very high default rate of 17.5 as compared to remaining categories , but number wise very less such rows with that category, also no significant difference in the default rates of remaining categories , so we conclude , home ownership has no effect on rate of defaults
- No significant difference of spread of defaulted/paid loans wrt dti
- No significant difference of spread of defaulted/paid loans wrt annual_income
- Slightly more chances of default if the funded amount is greater than 13000
- No significant difference of spread of defaulted/paid loans wrt installment




## Technologies Used
- [Python](https://www.python.org/) - version 3.12.4
- [Matplotlib](https://matplotlib.org/) - version 3.8.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2


## Acknowledgements

- This project was inspired by Upgrad IIIT, Bangalore and developed as part of the Exloratory Data Analysis Module as a case study for the Machine Learning and Artificial Intelligence course required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.

## Contact
Created by [@saradaparida](https://github.com/saradaparida) and [@sdakshinkar](https://github.com/sdakshinka)  - feel free to contact!

## License
This project is open source and available without restriction.'



