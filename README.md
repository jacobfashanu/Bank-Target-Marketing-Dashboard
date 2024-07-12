# Bank-Target-Marketing-Dashboard
Analyzing data from a bank's marketing campaign aimed at acquiring more deposits from customers. The dashboard was created with Excel and is available to download in this repository.

![](./excel-dashboard-screenshot1.png)
![](./excel-dashboard-screenshot2.png)

## Goals of the analysis
* See see which factors appear to influence customers’ decision to subscribe to term deposits
* By understanding the contributing factors to customer subscription behaviour, the bank can tailor their marketing strategies to improve their chances at acquiring more customers

## Data Acquisition
* The dataset is fictitous and was acquired from kaggle: https://www.kaggle.com/datasets/seanangelonathanael/bank-target-marketing 

## Data Cleaning/Preparation 
* Removed the age column and added an age range column
* Capitalized the data in the Marital status and Educational level columns
* Grouped the data in the average yearly bank balance, contact duration, # of times customer was contacted, and # of days since last contacted

## Metrics and Dimensions
* Age Range: Categorized ages of the bank’s customers
* Job: The line of work the customer is in
* Marital Status: Whether or not the customer is Married, Single, or Divorced
* Education Level: The amount of schooling completed by the customer. Ranges from High School to Masters
* Average Yearly Bank Balance: The average amount of money customers have
* Housing Loan: Whether or not the customer has a mortgage
* Number of Times Customer was contacted: Number of times the customer was contacted during this campaign
* Number of days since last contacted: The number of days since a representative contacted the customer for the previous campaign
* Outcome: Whether or not the customer ended up making a deposit

## Summary of Insights
* Unfortunately most customers did not end up making a deposit, specifically only 18.76% ended up subscribing to term deposits
* However, the highest percentage of successful deposits was amongst students at 41%, followed by retirees at 33.93%
* Customers contacted less were more likely to make a deposit
* Education did not seem to significantly impact whether or not a customer would subscribe to a term deposit. The same applies to marital status
* The existence of a housing loan however did impact a customers willingness to subscribe. Specifically, those who did not have a mortgage subscribed to a term deposit at twice the rate of those who have a mortgage

## Recommendation & Next Steps
* For the future, the bank should look to focus its efforts on marketing to students. They seem to be the most eager to make deposits
* Prospective customers should be contacted less. Otherwise the person being contacted mights feel bothered and harassed.
* Investigations should be done to better understand why customers who do not have a mortgage were more likely to subscribe to a term deposit than ones without one.


