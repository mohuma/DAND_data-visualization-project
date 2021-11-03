# Prosper Loan Data Exploration
## Dataset
Prosper Loan Data

This data set contains 113,937 loan records with 81 variables on each loan,
including loan amount, borrower rate (or interest rate), current loan status,
borrower income, and many others.

While the dataset contains loan data from pre-2009, some of the variables are
populated only after 1-July-2009. So, I restricted my analysis to only the loan
records created after this date.

## Summary of Findings
Analyzing the data from an investor's perspective, I found that there was a
strong positive linear relationship between Estimated Return and Borrower Rate.
Both these variables had negative relationship with Loan Amount and borrower's
Credit Score and no relationship with borrower's Debt to Income ratio.

While Borrower Rate had prominent variation between levels of the categorical
variables: Prosper Rating, Prosper Score, Loan Term and borrower's Income Range,
the same was not applicable to Estimated Return. More plotting was required to
predict the Estimated Return. Between Prosper Rating and Prosper Score, there
was a strong positive relationship.

Prosper Rating is a better predictor of Estimated Return. Their relationship is
in the shape of a candy cane. While moving from the best rating ("AA") to the
worst rating ("HR"), the Estimated Return increases up until the penultimate
rating ("E") and then drops.

Prosper Score is not as clear as Prosper Rating in its relationship with
Estimated Return. For each Prosper Rating level, different Prosper Score provides
higher Estimated Return. By looking at the Prosper Score alone, we can't say
whether it can provide higher Estimated Return. However, combined with
Prosper Rating, it can be used as an indicator of Estimated Return.

## Key Insights for Presentation
For the presentation, I will focus on Borrower Rate, Prosper Rating and
Prosper Score and their relationship with Estimated Return.

I will start by discussing Estimated Return first and then Borrower Rate. Then
I will show how they are related to each other using scatter plot and to the
categorical variables using violin plot.

Finally, I will show how Prosper Rating fits into the relationship between
Estimated Return and Borrower Rate using scatter plot. I cannot do the same for
the Proper Score. Instead I will be using a point plot to show how Prosper
Rating and Prosper Score are related to Estimated Return.
