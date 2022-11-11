# Loan Date from Prosper
## by Mustapha Aminu Saleh


## Dataset

The dataset contains 113,937 loans with 81 variables on each loan. The variables include loan amount, loan status, the occupation of the borrower, the reasons for borrowing and many others.
The data can be access from [here](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1666568105268918&usg=AOvVaw3PTcnMyadjrvXUqgl7JoI7)
While the details on variables can be accessed from [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1666568105270948&usg=AOvVaw0eguqkKN8UA-Iv-E1TKLOk)

My analysis was focused on the general properties of the borrowers and also factors 
that could influence their likelihood of completing their loans.
Resultantly, i selected some features out of the 81 available to make my work neat and 
focused.
Also, I dropped all current loan and reclassified the other loans in two groups. The first
group was for all completed loans while the second consisted of the defaulted loans.
Preliminary analysis revealed that the outliers in the monthly income columns could affect my
analysis, as such the upper and lower 10% of the column were dropped.


## Summary of Findings


In the exploration, it was that majority of the loans were completed and had a 36
months loan term. There was a higher proportion of home owners among the borrowers.
The distribution of the amount borrowed was skewed to the right, with majority
on the lower end. Like the loan amount, monthly income of the borrowers is also
more on the lower end. Information on the reason for borrowing was majorly not 
available. The interest rate and APR was mostly around 0.3.
During the bivariate exploration, i noticed that students took the least loans 
and also earned the least. Recreational Vehicles were the reason the highest 
loan amount borrowed on the average. The occupation with highest amount loaned 
was pharmacist. It was also noted that completion of loan was more among the those 
that earn more. Borrowers who were from Nebraska, students of technical school, 
and part-time workers had a higher loan completion rate. Loans with 12 months term 
are more likely to be completed that others. There seem to be a positive correlation 
between the loan amount and monthly loan payment.
Multivariate analysis focused on the relationship between the APR/Rate, loan amounts, 
and loan status. Surprisingly, the higher loan amounts with high APR/interest rates 
were more unlikely to lead to completion of loan.


## Key Insights for Presentation


For the presentation, i focused on the loan status and factors that might 
influence it. First, I visualized the proportion of loans completed and 
defaulted. Next, a boxplot was used to determine the relationship between the
monthly income of borrowers and loan status. The loan term was plotted against 
loan status to determine relationship.
Finally, Interest rate was plotted against loan amount with color encoding for 
the loan status.

