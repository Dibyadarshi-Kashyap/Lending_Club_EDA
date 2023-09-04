# Lending_Club_EDA
## INTRODUCTION:

Located in San Francisco, California, LendingClub is a US peer-to-peer lending business. It was the first peer-to-peer lender to provide loan trading on a secondary market and to register its offerings with the Securities and Exchange Commission (SEC) as securities. LendingClub is the world's largest peer-to-peer lending marketplace.

Our understanding of how real business challenges are resolved with EDA will be improved by solving this case study. We will also gain a fundamental grasp of risk analytics in banking and financial services through this case study, as well as how data is used to reduce the risk of financial loss when lending to clients.

## DESCRIPTION OF PROJECT:
The biggest losses are incurred by defaulting borrowers, which decreases cash flow for lenders. Finding those candidates who pose a risk helps the firm reduce the amount of credit loss. 
The 'loan.csv' data set was used for this analysis.

## DATA DICTIONARY:

| LoanStatNew | Description |
| --- | ------ |
| zip_code |	The first 3 numbers of the zip code provided by the borrower in the loan application.
|addr_state |	The state provided by the borrower in the loan application
|annual_inc |	The annual income provided by the borrower during registration.
|collection_recovery_fee |	post charge off collection fee
|collections_12_mths_ex_med |	Number of collections in 12 months excluding medical collections
|delinq_2yrs |	The number of 30+ days past-due incidences of delinquency in the borrower’s credit file for the past 2 years
|desc |	Loan description provided by the borrower
|dti|	A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
|earliest_cr_line |	The month the borrower’s earliest reported credit line was opened
|emp_length|	Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.
|emp_title|	The job title supplied by the Borrower when applying for the loan.
|fico_range_high|	The upper boundary of range the borrower’s FICO belongs to.
|fico_range_low|	The lower boundary of range the borrower’s FICO belongs to.
|funded_amnt|	The total amount committed to that loan at that point in time.
|funded_amnt_inv|	The total amount committed by investors for that loan at that point in time.
|grade|	LC assigned loan grade
|home_ownership|	The home ownership status provided by the borrower during registration. Our values are: RENT, OWN, MORTGAGE, OTHER.
|id|	A unique LC assigned ID for the loan listing.
|initial_list_status|	The initial listing status of the loan. Possible values are – W, F
|inq_last_6mths|	The number of inquiries by creditors during the past 6 months.
|installment|	The monthly payment owed by the borrower if the loan originates.
|int_rate|	Interest Rate on the loan
|is_inc_v|	Indicates if income was verified by LC, not verified, or if the income source was verified
|issue_d|	The month which the loan was funded
|last_credit_pull_d|	The most recent month LC pulled credit for this loan
|last_fico_range_high|	The last upper boundary of range the borrower’s FICO belongs to pulled.
|last_fico_range_low|	The last lower boundary of range the borrower’s FICO belongs to pulled.
|last_pymnt_amnt|	Last total payment amount received
|last_pymnt_d|	Last month payment was received
|loan_amnt|	The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.
|loan_status|	Current status of the loan
|member_id|	A unique LC assigned Id for the borrower member.
|mths_since_last_delinq|	The number of months since the borrower’s last delinquency.
|mths_since_last_major_derog|	Months since most recent 90-day or worse rating
|mths_since_last_record|	The number of months since the last public record.
|next_pymnt_d|	Next scheduled payment date
|open_acc|	The number of open credit lines in the borrower’s credit file.
|out_prncp|	Remaining outstanding principal for total amount funded
|out_prncp_inv|	Remaining outstanding principal for portion of total amount funded by investors
|policy_code|	Publicly available policy_code=1, new products not publicly available policy_code=2
|pub_rec|	Number of derogatory public records
|purpose|	A category provided by the borrower for the loan request.
|pymnt_plan|	Indicates if a payment plan has been put in place for the loan
|recoveries|	post charge off gross recovery
|revol_bal|	Total credit revolving balance
|revol_util|	Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.
|sub_grade|	LC assigned loan subgrade
|term|	The number of payments on the loan. Values are in months and can be either 36 or 60.
|title|	The loan title provided by the borrower
|total_acc|	The total number of credit lines currently in the borrower’s credit file
|total_pymnt|	Payments received to date for total amount funded
|total_pymnt_inv|	Payments received to date for portion of total amount funded by investors
|total_rec_int|	Interest received to date
|total_rec_late_fee|	Late fees received to date
|total_rec_prncp|	Principal received to date
|url|	URL for the LC page with listing data.
## CONCLUSIONS:
OBSERVED DRIVING FACTORS FOR CHARGING OFF-
1) Borrowers with a high-interest rate and a long employment length (10+ years).

2) Borrowers living on a mortgage with a loan amount greater than 12000.

3) Loan for debt consolidation, credit card, small business with an average loan amount greater than 12000

4) 60-month term tenure loans with 15-20% interest rates.

5) 36-month tenure loans with 10-15% interest rates.

6) Borrowers from grades E, F, and G with an average loan amount of 15000 or more.

## TECHNOLOGIES USED:

1) Python - version 3.10.12

2) NumPy - version 1.23.5

3) Pandas - version 1.5.3

4) Matplotlib - version 3.7.1

## REFERENCES:
1) [Case Study](https://www.researchgate.net/publication/340395124_Project_Lending_Club_Data_Analysis)
2) [Lending Club- Resource Centre](https://www.lendingclub.com/resource-center/personal-loan/what-to-do-if-you-are-declined-a-personal-loan)

6) Seaborn - version 0.12.2

