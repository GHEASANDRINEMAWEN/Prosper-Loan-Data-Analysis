# Prosper-Loan-🏦 DataSet-Analysis 📊

## Installations
- Python 3
- Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks.
- Numpy
- Pandas
- Matplotlib
- Seaborn

## Dataset

The dataset used for this project is the Prosper Loan Dataset. Which contains data about the details of the various loans lent to the borrowers and each row in the dataset represents a loan, uniquely identified by the Listing Key. Every row in the dataset describes various attributes about the Borrower such as Employment Status, Credit Score, etc. Every row also describes other parameters such as Monthly Payments, On Time Payments, Interest Rate, etc.


## Summary of Findings

The objective of this work is to investigate factors affecting borrower rate and loan amount:

In the exploration, I found that there was a moderate and negative 
correlation between interest rate and Loan amount. Also, there's negative 
and strong relationships between the categorical/ordinal variables selected and the interest rate. 
As an example, Unemployed people have more restrictive credit condition (higher rate) than the people who have jobs. 
The second factor is that borrowers who have collaterals(or homeowners) have lower rates than those who doesn't have 
any collateral(house).The third determinant is that borrowers with higher monthly salaries tend to get a lower lending 
interest rate. So it's a good determinant as well. Similarly, there is a strong indication that the Prosper score and 
rating is an excellent determinant factor of borrower's rate. We can conclude that the higher the score, 
the lower the rate.



The exploration of the dataset, led to the identification of some interesting dependencies 
between the Borrower's Attributues and Loan Attributes.

- Borrowers with Higher Monthly Income are assigned a Higher Prosper Score.
- Borrowers with Prosper Score higher than or equal to 8, are more likely to own a home, when compared to those with score less than or equal to 7.
- Employed Borrowers take loans of Higher Amounts when compared to Borrower's who are Retired or Unemployed.
- Unemployed Borrowers are charged a Higher Interest Rate in comparison to Employed and Retired Borrowers.
- Employed Borrowers are assigned a Higher Prosper Score.
- The Interest Rate is Negatively Correlated with Prosper Score. Higher Prosper Score leads to Lower Interest Rates.
- The Loan Amounts given has constantly increased over the years.
- Higher Loan Amount also leads to a Higher Loan Term.
