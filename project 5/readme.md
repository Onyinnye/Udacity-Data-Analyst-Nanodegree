#### Loan Data From Prosper
- The Loan data set from propsper contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate)current loan status, borrower income, and many others
- The aim of the project is to  explore different variables in the dataset to know how they affect granting and recieving loan.
- I focused my explortion on factors that affect a borrower chances of receiving the loan when applied for and factors that affect the Prosper Score
-  I used These  features in the dataset BorrowerState, IncomeVerifiable, Occupation,EmploymentStatus,BorrowerRate, IsBorrowerHomeowner, ListingCategory_Numeric,Recommendations, MonthlyLoanPayment, LoanOriginalAmount,LoanOriginationDate, LoanStatus, DebtToIncomeRatio, IncomeRange, ProsperScore, StatedMonthlyIncome, PercentFunded
#### Visiualization
- I visualized categorical univariate and quantitative Univariate variables and had the following obseravations
#### Categorical Univariate
- from the visual, majority of the borrowers are from CA 
- From the visual, the occupation registered as other applied for loan more followed by the profesionals
- from the visual, borrowers from category 1( Debt Consolidation) applied mostly for loan
- From the visual, the employed mostly applied for loan
- from the visual, the 50,000- 74,999 income range applied more for loan
- From the visual, the most occuring score is the 8 score followed by the 6 score
#### Quantitative Univariate
- The highest applicable borrower rate is the 0.15 rate since it is the highest occuring rate
- From the visual, the highest stated monthly income is about 6000
- from the visual, the highest original amount requested by borrowers is about 6000
- From the the visual, the highest percent funded is 1 which means that almost everyone recieved the amount they applied for
- From the visual,  the highest monthly payable loan is about 200 dollars

#### Categorical Univariate
- The income range contained an "Not employed row which I excluded for thee visualiztion
- The Prosper Score had 1392 rows of 11 values which I remove since 10 is the  best or lowest risk score
#### Quantitative Unnivariate
- This visualfor the stated monthly income and original amount requested does not really give an insight on the values of the stated montly income, so I set bins
- I visualized  bivariate variables of (2 quantitative variables, 1 quantitative and categorical variables and 2 cattegorical variables) and had the following observtions:
- From the visual, the loan original amount is highly corelated with the monthly loan payment. This means that the monthly loan payment is highly dependent on the amount of loan granted
- FRom the visual, we saw that the borrowers in the lowest income range(1 - 24,999 dollars) had the highest raate than other income range
- From the visual, we se that having a house does not guaranty complete loan request since the non home owners have more numbers of completed loans than home owners 
-  visualized multivariate variables and had the followinng observations:
- From the visual, Self employed borrowers with prosper score rating 10 had the highest stated monthly income
- From the visual, all borrowers with prosper score 10 mostly had the highest income rate although the self employed has the highest monthly stated income
- frrom the visual, the Prosper Score 10 increased as the income range inncreased. this means that people with high income range that apply for high loan original amount are most likely to have prosper score 10
#### Summary and Observations
- Borrower Rate increased for lower income range borrowers
- The higher the loan requeted, he higher the monthly loan payment
- Having a house does not guarantee loan status would be completed
- Prosper Score is dependent on employment status, stated monthly income and income range of borrowers
- The income range( 50,000- 74,999) have the highest loan request
- Loan approval status and the Prosper Score is dependent on the income rate, employment status and occupation


```python

```
