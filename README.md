# Marketing Target Analysis 
Machine Learning Classification : Marketing Target Analysis 
Time deposits are one of the savings products provided by banks to their customers besides regular savings. Deposits are banking products where customers deposit a certain amount of money to be stored in the bank for a long period of time. This money cannot be withdrawn before a specified period of time, for example 1 year, 5 years or 10 years. The advantage of deposits obtained by customers is that the bank's interest rate offered is higher than other banking products.
One of the most effective ways to reach out customers is by Telephonic Marketing Campaign. However, the cost of running this campaign is quite expensive. The bank needs to invest in supporting properties and hire a lot of call centers to execute this campaign.
Hence, it is important to identify the customers most likely to subscribe the campaign. By creating a model to helps the marketing team work in effective and efficient way, the bank could lead to significant cost reduction. 
(Source: https://www.kaggle.com/code/berkinkaplanolu/banking-analyze/notebook)

What to find out?
(a)	Which features contributes high subscribed rate?
(b)	Which analytics model has the highest score prediction for Banking Dataset?
(c)	What strategy the marketing team could use to succeed in their campaign?

Data Acquisition
Marketing Target Analysis dataset was obtained from kaggle.com
The data set includes information about:
•	Customer’s age – the column is called age
•	Customer type of job– the column is called job
•	Customer’s education level – the column is called education
•	Outcome of the previous marketing campaign – the column is called poutcome

Data Dictionary
Marketing Target Analysis Attribute Information (in order):
1 - age (numeric)
2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
"blue-collar","self-employed","retired","technician","services")
3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
4 - education (categorical: "unknown","secondary","primary","tertiary")
5 - default: has credit in default? (binary: "yes","no")
6 - balance: average yearly balance, in euros (numeric)
7 - housing: has housing loan? (binary: "yes","no")
8 - loan: has personal loan? (binary: "yes","no")
# related with the last contact of the current campaign:
9 - contact: contact communication type (categorical: "unknown","telephone","cellular")
10 - day: last contact day of the month (numeric)
11 - month: last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec")
12 - duration: last contact duration, in seconds (numeric)
# other attributes:
13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
15 - previous: number of contacts performed before this campaign and for this client (numeric)
16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

Output variable (desired target):
17 - y - has the client subscribed a term deposit? (binary: "yes","no")

Missing Attribute Values: None
