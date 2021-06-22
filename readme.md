# Prosper Loan Data Analysis
## by Xinqi Lin


## Dataset

> The dataset of Prosper Loan contains 113,937 rows and 81 columns. 
Most variables are numeric, some are categorical, boolean and date. 
Variables like ProsperRating (Alpha) and IncomeRange can be ordered 
factor variables with the following levels. 
Some of the variables have a lot of null values, such as variables prosperrating and prosperscore, 
which I'll need to deal with. Some variables are not of much use, 
such as listingkey, listingnumber, of other identifiers, which I did not include in my analysis.


## Summary of Findings

> I found some variables that are correlated with a loan being default or not, such as borrower rate,
income, credit score, listing categories, state, and debt to income ratio. 
Borrower rate, and debt to income ratio have positive correlation with default rate. Income and credit score have
negative correlation. Certain states and listing categories have higher default rate than others.


## Key Insights for Presentation

> For the presentation, I focus on the correlation between the variables and main varible of interest Default.
I start by introducing the default variable, followed by plotting the correlations.

I introduce each of the categorical variables one by one. To start,
I use the box plots of default and borrower rate. Then I showed the correlation between default and income group
using bar chart.
Last, I showed a grid box plot showing the relationship among default, credit score range lower, and borrower rate.
