# Lending Club Risk Analytics Case Study
> Analyzing loan data to identify key factors influencing defaults and minimize financial losses.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project involves a detailed Exploratory Data Analysis (EDA) on loan data from Lending Club.
- **Background**: The objective is to understand patterns and variables that influence loan defaults to help Lending Club reduce credit losses and make informed lending decisions.
- **Business Problem**: Lending Club faces two major risks:
  1. Loss of business when loans to eligible applicants are rejected.
  2. Financial loss when loans are approved for applicants likely to default.
- **Dataset**: Historical loan data from 2007 to 2011, including attributes like loan amount, interest rate, term, grade, employment length, and outcome (e.g., fully paid, charged-off).

## Conclusions
1. Approximately **14.5% of loans default**, with higher rates among borrowers with 36-month terms and loan amounts between $5,000 and $16,000.
2. Borrowers with **DTI ratios between 9 and 20**, annual incomes of $37,000-$75,000, or rented/mortgaged homes are at higher risk of default.
3. Geographically, **California (16%), Florida (18%), and New York (13%)** have the highest default rates, necessitating additional scrutiny.
4. Loans graded **B** have the highest default counts. Defaults decrease from grades B to G, with grade G having the least defaults despite higher interest rates.
5. Borrowers with **loan purposes such as debt consolidation, credit cards, and small business** show high default rates, requiring stricter assessments.
6. Borrowers in the **10-16% interest rate range** have a higher likelihood of defaulting.

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
Created by @vijaykumar-qait, @ Nagshan171985

