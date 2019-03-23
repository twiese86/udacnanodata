# ProsperLoan Analysis of Defaults
## by Thomas Wiese


## Dataset

The dataset used was the ProsperLoan dataset provided by Udacity. The data dictionary can be found here: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

and the original dataset can be found here:
https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv.


## Summary of Findings
To look at the relationship between interest rate, and risk level to see if there was a direct corrleation with wether or not loans would default. I would hypothesize that the lower interest rates (closer to 0) and highest prosperscore (11 being lowest risk) would have the lowest levels of default. We can see from the plot that the loans with the highest rtes are the highest risk We can also see that as risk decreases, generally default rate decreases, however, this is not universally true. 

## Key Insights for Presentation

What surprised me here is that after about a prosperscore of 6 the consistent trend seems to change, and at a prosperscore of 10 even reverses. This would lead me to believe there may have been a flaw in how the prosperscore was calculated pr how the data was collected
Interestingly, different states and different loan types had clearly different default rates
For example,  Alambamas defaulted 42% of the time, while Northern Virginians defaulted 22% of the time