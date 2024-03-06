# Lending Club Case Study
> Help a finance company identify risky loan applicants
Understand consumer attributes and loan attributes that are likely to cause the account to be defaulted

## Table of Contents 
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project uses univariate, segmented, bivariate and multivariate analysis on consumer loan data to identify risk factors in consumers applying for loan
- https://www.lendingclub.com/
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- Dataset: complete loan data for all loans issued through the time period 2007 t0 2011.


## Conclusions
- People with employment length more than 10 years or less than 1 year are likely to default
- Lower income group(upto 90000) is likely to default
- High Interest Rate, high loan amount is likely to default.
- High loan grades have higher interest rate which increases loan risk.
- People with public reported bankrupticies are highly likely to default


## Technologies Used
argcomplete 3.1.1
click       8.1.7
colorama    0.4.6
jsonpickle  3.0.2
packaging   23.1
pip         23.1.2
pipx        1.2.0
setuptools  65.5.0
userpath    1.9.0
pandas      2.0.3
numpy       1.24.3


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Google search to understand banking terms and loan attributes


## Contact
Created by [@chetnapriyadarshini & @CodingWithNitish] - feel free to contact me!
