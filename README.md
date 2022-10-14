# (Proper Loan Data Visualization)
## by (Olamide SHOGBAMU)


### Proper Loan Data Visualization

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, borrowers occupation, home ownership status of borrowers, and many others.

A copy of this data is hosted on GitHub [Here](https://github.com/TheSHOGBAMU/Data_Visualization/blob/main/ProsperLoanData.csv), and a detailed dictionary for the column head can be found in an excel sheet [here](https://docs.google.com/spreadsheets/u/0/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing). 

This visualisation project investages factors that affects Loan Status and Prosper Score. Factor that affect Borrowers Annual Percentage Rate, the highest loan amount, the influence of borrowers home ownership status, the reason listed for borrowing and so on.


### Summary of findings

- The highest loan amount borrowed ranges from 2000 to 4000 with approximately 30,000 records that falls in the range. The lowest loan amount is between 0 and 1000 with a total of 3206.


- Most people collect loan to consolidate debt while a reasonable large number of individual take loan for reasons they are not willing to disclode.


- Low prosper score has high annual rate. However, the higher the prosper score the higher the lender yield. Also, we see that most of the borrower have a low customer risk score of 4 - Prosper Score, followed by a score of 6, 8 and 7.


- Borrowers home ownership status increased along the year from false to true, however the Borrowers Annual Percentage Rate is independent of his two variables.


- The status of the loan is independent of the term of the loan, although the current loans also have the longest term which is 60 month. Every loan status seems to have the same loan term.


- Employed set of people and people with full time occupation has the most record the loan dataset. Also Califonia has the most employed loan borrowers, followed by Texas and New York. Hence, it is logical to say that Employed people from Califonia borrowed the most loan.


- The outcome of a loan depends of the past performance of customers (the Prosper Score). Borrower with defaulted and charged-off loans have and Prosper Score of 6 While, the Prosper Score for borrowers with loans that have past due dates is 4


- Some values of important features on the dataset are null



## Key Insight

Finding the factors that affects the status of a loan becomes an important problem to solve as it helps the firm to enlighten their customers and helps the customer to which aspect to consider. 

Prosper Score has help us solve this problem to an extent and connect us to more feature that can help in answering this question such as Debt.

I approached this problem using Matplotlib and Seaborn's visualization tools. I plotted a group bar plot of prosper score together with other features to visualise this observation. A scatter plot to show the relationship between Prosper Score, Borrowers APR and Lenders Yield which can be used to measure a successful loan.