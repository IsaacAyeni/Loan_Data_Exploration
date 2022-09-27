# Prosper Loan Data Exploration

## Dataset
The data consists of information regarding 113,937 loans with variables including the borrower rate, loan original amount and other variables all together making up 81 variables.
The dataset can be found at the link[here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) and feature documentation available[here](https://docs.google.com/spreadsheet/ccc?key=0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE&usp=sharing)



## Summary of Findings

In the exploration, I discovered that the borrower rates had strong relationships between several other features. The most notable of these features are the borrower APR, Prosper ratings, Estimated loss, estimated returns, lender yield and the estimated effective yield. There were also some features which showed some interesting relationships with the borrower rate although theirs were not as strong as the aforementioned features. These features are the loan original amount and the credit upper score range.

For the Estimated loss the relationship is linear when the borrower rate is transformed to be on a square-root scale. The lender yield has a strong positive linear relationship with the borrower rate even without carrying out any variable transformation and it can be inferred that the lender yield strongly depends on the value of the borrower rate. 
A negative relationship is observed between the Prosper rating and the borrower rates as the highest Prosper ratings end up on the low end of the borrower rate and the case is reverse for the lower Prosper ratings. Similar to the Prosper ratings, a negative relationship is observed between the Loan original amounts and the borrower rates, although the relationship of the loan original amount is somewhat moderate and not as strong as the relationship between the borrower rate and Prosper rating.

An interesting finding was made on the data about the borrower rates. It was discovered that across the credit score range upper values, the average value of the borrower rates decreases and when the borrower rates are grouped into categories based on the employment status the borrowers with not-employed as their employment status have the highest average borrower rates.

Outside of the main variables of interest, between the categorical variables which were majorly the Employment status, the Loan term and the ProsperRating, the Loan term of 36 months was found to have the greatest count across all the categories of both the Employment status and the ProsperRating.


## Key Insights for Presentation

For the presentation, I focus on the variables that are affected by and or affects the borrower rate to a relatively great extent. I'll start by introducing the borrower rate variable, followed by the pattern in the Estimated loss, then plot the
transformed scatterplot.

After that I'll introduce the Prosper rating which is the most significant of the categorical variables. Then the relationship between the Prosper rating and the borrower rate is shown with the aid of violin plots. The presentation is then brought to an end by showing the average borrower rate by the upper credit score range for all employment status with the aid of a pointplot.

