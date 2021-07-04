# Data Analysis Report - Prosper Loan Data
## by Johnny Yamanaka

<br/>

## Dataset
<div style="text-align: justify">
  The <a = href='https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000'>original data set</a> contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. For this analysis, I chose to reduce data set to 71,052 loans and 27 variables.
</div>

## Summary of Findings
* About Loam amount:
  * Most of loan are into \$0 to \$15k range;
  * Borrower with income below \$50k does not borrow higher values, in fact, usually they borrow until \$10k;
* Debit consolidation was the most common loan reason in all social classes;
* Generally, loan with great amount has lower borrower rate;
* About prosper rating:
  * Better prosper rating gives to borrower lower rate to loan;
  * Prosper rating are related with loan amount - that indicated that borrower with higher rating can borrow more money.
* Some variables has no influence borrower rate, like employment duration and on time payments.
