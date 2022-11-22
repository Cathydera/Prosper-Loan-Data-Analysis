# Prosper-Loan-Data-Analysis
## by Catherine Nwachukwu


## Dataset
> The Prosper loan data set contains 113,937 loans with 81 variables on each loan, including Prosper Loan Rating, current loan status, borrowers occupation, employment status and many others. To have access to the dataset and data-dictionary, click on this link: [Udacity hosted dataset dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

> The following libraries were used in this project:
- NumPy
- pandas
- Matplotlib
- Seaborn
- Squarify
- Plotly

> Data wrangling steps performed before exploration includes:
- Removal of empty and NAN values
- Reformatting of occupation column with multiple titles for the same profession
- Converting the data types in columns to the appropriate data types


## Summary of Findings

> One of the most important factors in borrowing is the Prosper rating. Depending on the rating, it is decided how high the interest repayment will be. The credit rating classification is also an indicator that the borrower is either likely to be able to repay the loan or is highly likely to default on the loan. Taken from this basis, the first factor of the analysis was the "Prosper Rating (Alpha)". I found that majority of the borrowers fell under **Prosper Rating Group C.**

> The second factor considered was loan status (Current, completed, chargedoff, defaulted and past due date). It was deduced that 44.9% of the loan (51170 loans) are still running as at the time of analysis. 

> Another important variable is the **"employment status"**. From this it can be deduced in which employment the borrower is, how high the monthly loan installment is and whether the borrower can repay the loan installment

Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.


## Key Insights for Presentation
> The focus on the presentation will be for retired people and their distributions across the rating, borrowers rate and loan instalment. 


- Effect of retirement on the prosper loan rating 
- Monthly loan instalment for retired people
-  Borrowers rate for retired people
