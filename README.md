# Lending Club Case Study
> Objective is to identify the risky loan applicants at the time of loan application so that such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

>In other words, to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. And thus minimise the risk of losing money while lending to customers..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Identifying the driving variables behind the loan default cases.
- The background of the project is "consumer finance company" called "Lending Club" which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
- Business Problem - This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. <br /><br /> Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. <br /><br />If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
- Database being used - Loan dataset that contains the complete loan data for all loans issued through the time period 2007 to 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- library - Pandas  - version 1.4.2
- library - numpy   - version 1.21.5
- library - seaborn - version 0.11.2
- library - matplotlib - version 3.5.1 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- Purpose of Loan - Small businesses are particularly risky, therefore should be cautiously sanctioned
- Interest Rate -  Higher rates are not deterrent to defaults and therefore denying loans to risky individuals may be better strategy than approving their loan with higher interest 
- Loan amount to Annual income ratio - Higher loan amount to annual income ratio is associated with higher chance for potential default. Therefore, annual income should be used as metric to determine the upper bound of loan amount

- Verification Status - 'Not Verified' customers are potential risk to the business. The Company should analyze more details of these borrowers before approving the loans
- DTI - The company has to focus more on lower dti loan applicants and stop approving the loans for higher dti applicants

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Contact
Created by [@sriram1188] , [@prajwalpmoolya] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
