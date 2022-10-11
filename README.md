# (PROSPER LOANS DATA EXPLORATION)
## by (Akiteng Gibson)


## Dataset

The document explores a data set containing 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The analysed data however,is a sample data set containing 22,655 pre-2009 loans with 15 variables on each loan, including ListingKey, ListingCreationDate, CreditGrade,Term, LoanStatus, ProsperScore, ListingCategory (numeric), EmploymentStatus, IsBorrowerHomeowner,IncomeRange, IncomeVerifiable, TotalProsperLoans, OnTimeProsperPayments, LP_CustomerPayments. The data after wrangling, a clean dataset of 17971 loans record remained.


## Summary of Findings

The loan repayment status and the the corresponding interest earnings is related to the borrowers characteristics including the credit grading. Looking on the correlation between loan status, LP_interestandFees and the employment status of the borrowers. The self-employed generally payed generated more LP_Interests and Fees while the unemployed(0 income) recorded the least. Between, the loan status, LP_interest/LP_Customerpayments and isBorrowerHomeOwner,it showed that borrowers who were home owners payed more LP_customerpayments while those who were not home owners payed less. Most of home owners borrowers completed their loan repayments compared to the non home owners. Also on loan status, LP_interestandFees and borrowers employmentstatus, It was evident that borrowers with an income range of 100,000+ recorded more LP_Interestand Fees while borrower with an income range of 1-24,999 dollors recorded the least. A lot of borrowers with an income range of 25,000-49,999 dollars completed their loans repayment and afew defaulted. A lot of unemployed of 0 income borrowers defaulted their loans. Most of the borrowers with C and D grading completed their loans repayments while most of the borrowers with grading of E and HR defaulted their loans.


## Key Insights for Presentation

For the presentation, I focused on just the effect of the borrower characteristics to his/her ability to repay the loan. I started by looking at the distribution of each borrower characteristics including emplyment status, is the borrower home owner, income ranges and the credit grade assigned to each borrower. I looked on loan status and the distribution of the customer payments and interests after loan repayment.

Afterwards, I looked on the correlation of each of the characteristics with lon status, LP_customer payments and LP_interestand fees. I used bar graphs and violin plot to analyze this data. I've made
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.
 
