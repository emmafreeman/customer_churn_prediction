# Problem statement

Customers come, and customers go.  We can assume network performance plays a role in customer satisfaction and thus the tendency of longevity of a customer, but can we gauge likelihood of churn on Customer Usage?

Utilizing the Usage profile of a customer, go through the data science workflow and build a classification model to predict whether or not an account will churn.

# Dataset

Timeframe: 6/1/2016 – 6/30/2017

Every row is one account’s first 30 days of Usage, and then whether or not the account was active on day 61.  

Columns:
account_num – customer’s account number
base – location of the customer
tenure – how long the customer has been/was with us
sessions – number of times a customer has signed-on during the first 30 days
duration – time in minutes a customer was online during the first 30 days
mega_bytes – amount of data consumed during the first 30 days
case_count – how many times a customer called us in the first 30 days 
comp_flag – does the base the customer is located at have any competitors
train_flag – is the base the customer is located at designated to be a training base
pcs_flag – was the account created during a season with high movement
holiday_flag - was the account created in November or December
churn – on day 61 since Account Creation, is the account active or inactive
