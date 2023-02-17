# (Dataset Exploration - Loan Data from Prosper)
## by (Noura)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. After exploring the documentation, these 17 features can be more important in this exploration: LoanStatus, ProsperRating (numeric), ProsperRating (Alpha), ProsperScore, EmploymentStatus, IsBorrowerHomeowner, Recommendations, InvestmentFromFriendsCount, Term, BorrowerAPR, BorrowerRate, ListingCategory (numeric), CurrentlyInGroup, IncomeRange, IncomeVerifiable, StatedMonthlyIncome, Investors. After that I applied some data wrangling and excluded the unneeded columns. I changed the ListingCategory and ProsperRating (Alpha) into cagorical variable using the appropriate values obtained from the documentation.


## Summary of Findings

**Univariate Exploration Results:**

> The distribution of APR looks multimodal with many peaks at different places. Most of the loans have APR between 0.05 and 0.4.

> The distribution of StatedMonthlyIncome is right screwed, with most of the values less than 20k.

> It seems that the current status is the highest. Whatsoever, the completed loans count is higher than the other status values.

> Debt Consolidation is the Listing Category with the highest value.

> The Employed status is the most, wheras Retired is the least.

> Majority of the people granted loans are Homeowners.

> Most of the borrowers do not belong to any group.

**Bivariate Exploration Results:**

> There are positive and negative correlations between some of the numerical values: BorrowerAPR & BorrowerRate +corr

> BorrowerAPR & BorrowerRate +corr

> BorrowerAPR & ProsperRating (numeric) -corr

> BorrowerAPR & ProsperScore -corr

> ProsperRating (numeric) & ProsperScore +corr

> ProsperRating (numeric) & BorrowerRate -corr

> ProsperScore & BorrowerRate -corr

> Recommendation & InvestmentFromFriendsCount +corr

> Investors & ProsperScore +corr

> Investors & ProsperRating (numeric) +corr

> Investors & BorrowerAPR -corr

> Investors & BorrowerRate -corr

> The loans with the Current and Completed status have got the highest Recommendations.

> There are more Current and Completed loans with investment from friends count.

> There are more Current and Completed loans with Higher ProsperScore.

> High IncomeVerifiable count with Employed status.

**Multivariate Exploration Results:**

> Appearantly, Term doesn't have effect on the relationship between BorrowerAPR and ProsperScore.

> The positive correlation between Investors and ProsperScore tends to be strengthen as the ProsperRating (Alpha) increases.

> It seems that borrowers who owned homes got more recommendations.

> LoanStatus does not have significant effect on the relationship between ProsperScore and EmploymentStatus

> It seems that, BorrowerHomeowners with Current and Completed loanStatus have higher ProsperScore.



## Key Insights for Presentation

> BorrowerAPR & ProsperScore -corr

> Investors & ProsperScore +corr

> Appearantly, Term doesn't have effect on the relationship between BorrowerAPR and ProsperScore.

> The positive correlation between Investors and ProsperScore tends to be strengthen as the ProsperRating (Alpha) increases.

