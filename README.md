# Lending Club Risk Analytics Case Study
> Analyzing loan data to identify key factors influencing defaults and minimize financial losses.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project entails a comprehensive Exploratory Data Analysis (EDA) of loan data from Lending Club.
- **Context**: The aim is to analyze patterns and variables affecting loan defaults to assist Lending Club in minimizing credit losses and making educated lending choices.
- **Business Problem**: Lending Club encounters two significant risks:
  1. Business loss resulting from the rejection of loans to qualified applicants.
  2. Financial loss incurred when loans are sanctioned for candidates prone to default.
- **Dataset**: Historical loan data from 2007 to 2011, encompassing attributes such as loan amount, interest rate, term, grade, employment duration, and outcome (e.g., fully paid, charged-off).


## Conclusions
1. Approximately **14.5% of loans default**, with elevated rates among borrowers with 36-month periods and loan amounts ranging from 5,000 to 16,000.
2. Borrowers displaying **DTI ratios ranging from 9 to 20**, yearly incomes between 37,000 and 75,000, or residing in rented or mortgaged properties are at an elevated risk of default.
3. California (16%), Florida (18%), and New York (13%) exhibit the greatest default rates, requiring further examination.
4. Loans classified as **B** exhibit the highest incidence of defaults. Defaults diminish from grades B to G, with grade G exhibiting the lowest defaults despite elevated interest rates.
5. Borrowers seeking loans for purposes such as debt consolidation, credit card repayment, and small company ventures have elevated default rates, necessitating more rigorous assessments.
6. Borrowers with interest rates between **10-16%** exhibit an increased probability of default.


## Technologies Used
- **Python**:
  - pandas - version 1.4.4
  - numpy - version 1.23.3
  - matplotlib - version 3.5.2
  - seaborn - version 0.11.2

## Acknowledgements
- This project was inspired by Lending Club’s need for improved risk analytics.
- Data sourced from Lending Club records.

## Contact
Created by @vijaykumar-qait, @Nagshan171985

