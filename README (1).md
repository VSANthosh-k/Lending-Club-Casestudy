# Project Name
> Solving this assignment will give you an idea about how real business problems are solved using Exploratory Data AnalysisDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.
## Bussiness understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

1.Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

2.Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

3.Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
## Bussiness objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## Conclusions
1.The % of charged off loans increases substancially as we go up the loan amount buckets. Most loans are below 20000 amount. The higher loans, though lesser in number, carry a substantially higher risk of default.
2.Around 75% of the total loans are given for duration of 3 years. while just 25% of the loans are those given for 5 years. Among Charged Off loans, percentage of term 60 months rises to 45%. The higher term loans have a higher chance of default
3.26% of loans for small business are Charged Off. Making them the most risky purpose. Approximately ~49% of the loans are issued for the purpose of dept consolidation. 17% of the loans for renewable_enrgy are charged Off, but the number is too less to be of significance.
4.The percentage of Charged Off loans is more when the borrower has a prior record of bankruptcy.
5.Overall, the intrest rate varies from 5.42% to 24.4% with average intrest rate of 11.8%. The intrest rate for Charged Off loans appear to be higher than for Fully paid. This is naturally expected. As, the risk increases the rate of interest imposed on the loan also increases
6.As the intrest rate increases there is a higher chances of defaulting the loan
7.the percentage of loans issued in the category of E,F,G are very less but percentage charged off loans are more in these category .hence the loans issued in the catogories E,F,G are more dangerous
8.There is no impact of employment length to chance of loan default.
9.There is no impact of home_ownership to default on loan.
10.Verified loans show more charged Off percentage as compared to Not verified loans
When the dti is higher than 20, higher percentage of loans are Charged Off Higher the dti higher the chances of loan being Charged Off
11.The number of 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years values ranges between 0 and 11. There are higher chances of default if this variable is increasing from 1
12.Higher loan amounts are Verified more often. We already know that larger loans are less in number, but see a higher charge off rate. This, combined with previous observation, explains why verfied loans see a higher rate of default. It's not the verified status per se, it's the fact that higher loan amounts are riskier and are also verified more often by Lending Club.
13.Higher loan amount are associated with lower grade for longer terms.
14.revol_util and grade(and therefore int_rate) are correlated in some way. The revol_util is positivly correlated to the grade. As the grade goes from A to E the revol_util also increases. This may be because higer loan amounts are accosiated with higher grades.
15.loan charged off has more correlation with intrest rate and then with revol_util means higher the intrest rate more the chances for charged off

## Technologies Used
-python-version 3.7.1
- matplotlib- version 3.0.2
- seaborn - version 0.11.2
- numpy - version 1.15.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@githubusername] - feel free to contact me!


