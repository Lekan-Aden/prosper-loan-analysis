# Prosper Loan Dataset
## by Lekan Adenusi


## Dataset

This document explores the prosper loan dataset provided by Udacity. For a bit of background, Prosper Loan is a loan-lending platform that offers personal loans to borrowers with a fixed interest rate. The data contains over 100,000 records and 81 attributes, of which I used only a few.

## Summary of Findings

I carefully explored how certain features of the data influence the Borrower Annual Percentage Rate. I started by exploring the APR as well as the other features that I had perceived could be useful for my analysis. From the univariate exploration, I observed that the distribution of the APR is almost normal with a few outliers and that employed persons form a major part of this dataset. Further, most of the continuous variables explored happen to be right-skewed and the loan amounts do not take just any value, but are mostly multiples of 1000 as revealed by the spikes in its distribution.

Of all the features examined, the loaned amount, prosper rating, income range, and credit scores, proved most useful. While I was able to uncover some exciting relationship between these variables and the APR, I also noticed how these variables strengthened themselves. For example, the proportion of loanees earning large amounts actually increases as the prosper rating becomes better, indicating that better prosper ratings can be found amongst the (relatviely) richer persons.

In conclusion, higher prosper ratings, loaned amount, credit scores, and income range reduce the APR and vice versa.

## Key Insights for Presentation
In my presentation I focus on how the loaned amount, prosper rating, and the income range affect the APR, as well as the exciting interactions observed between them.