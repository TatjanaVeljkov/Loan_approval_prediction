# Loan_approval_prediction
## Problem description:
Classification to predict whether a credit would be approved or not for a client.

Field Name	Order	Type (Format)	Description
checking_status	1	string (default)	Status of existing checking account, in Deutsche Mark.
duration	2	number (default)	Duration in months
credit_history	3	string (default)	Credit history (credits taken, paid back duly, delays, critical accounts)
purpose	4	string (default)	Purpose of the credit (car, television,…)
credit_amount	5	number (default)	Credit amount
savings_status	6	string (default)	Status of savings account/bonds, in Deutsche Mark.
employment	7	string (default)	Present employment, in number of years.
installment_commitment	8	number (default)	Installment rate in percentage of disposable income
personal_status	9	string (default)	Personal status (married, single,…) and sex
other_parties	10	string (default)	Other debtors / guarantors
residence_since	11	number (default)	Present residence since X years
property_magnitude	12	string (default)	Property (e.g. real estate)
age	13	number (default)	Age in years
other_payment_plans	14	string (default)	Other installment plans (banks, stores)
housing	15	string (default)	Housing (rent, own,…)
existing_credits	16	number (default)	Number of existing credits at this bank
job	17	string (default)	Job
num_dependents	18	number (default)	Number of people being liable to provide maintenance for
own_telephone	19	string (default)	Telephone (yes,no)
foreign_worker	20	string (default)	Foreign worker (yes,no)
accepted	21	string (default)	Class

## Steps applied: 
-	EDA techniques for analysis
-	Target Variable Analysis
-	Univariate analysis of Categorical Features
-	Bivariate analysis of Categorical Features
-	Analysis of Numerical Features
-	Detect missing values and handle them
-	Transformation of Numerical Features (scaling & encoding)
-	Train/test split: with train (70%), test (30%) with random_state = 0
-	Train the model
-	Evaluate the model
-	
## Target: Achieve accuracy on test set >=0.90
