# Lending Club Risk Analytics Case Study
> Analyzing loan data to identify key factors influencing defaults and minimize financial losses.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This project requires a full Exploratory Data Analysis (EDA) of loan data from Lending Club.
- **Background**: The objective is to search for patterns and variables that affect loan failures so that Lending Club can reduce credit losses and make smart lending decisions.
-- **Business Problem**: Lending Club faces two major risks:
  1. A loss of business due to not giving loans to qualified prospects.
  2. The money that is lost when loans are provided to people who are likely to not pay them back.
- **Dataset**: Historical loan data from 2007 to 2011, including loan amount, interest rate, term, grade, length of work, and outcome (e.g., fully paid, charged-off).


## Conclusions
1. Approximately 14.5% of loans have not been paid back, and the rate is higher for individuals with 36-month terms and loan amounts between 5,000 and 16,000.
2. People with **DTI ratios** between 9 and 20, yearly incomes between 37,000 and 75,000, or homes that are rented or mortgaged are more likely to not pay back their loans.
3. The highest rates of failure are in California (16%), Florida (18%), and New York (13%), which needs more research.
4. Loans with a grade of **B** have the highest rate of defaults. From grade B to grade G, defaults go down, with grade G having the lowest defaults even though interest rates are high.
5. Individuals who want loans for items like paying off credit cards, consolidating debt, or starting a small business have higher rates of default, which means that lenders have to be more careful when evaluating these people.
6. Individuals who borrow money with interest rates between 10% and 16% are more likely to not pay back their loans.



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

