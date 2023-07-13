## Statistical Data Analysis Project
Author: Andrew Kwon

## Description
Statistical data analysis, data visualization, and hypothesis testing on customer usage data for the telecom company, Megaline. Python code, comments, and analysis conducted in Jupyter notebook.

## Introduction

We are provided data from the telecom operator, Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget. We'll conduct a preliminary analysis of the plans based on a relatively small (500) client selection in order to analyze behavior and determine which prepaid plan brings in more revenue. Additionally, we'll conduct hypothesis testing regarding average revenue between users of both plans (one-tail test) as well as comparing the average revenue between two regions (equality of means of two sample populations).

## Dataset

**megaline_users.csv**
- *user_id*: unique user identifier
- *first_name*: user's name
- *last_name*: user's last name
- *age*: user's age in years
- *reg_date*: subscription date (YYYY-MM-DD)
- *churn_date*: the date the user stopped using the service (if the value is missing, the calling plan was being used when this database was extracted)
- *city*: user's city of residence
- *plan*: calling plan name

**megaline_calls.csv**
- *id*: unique call identifier
- *call_date*: call date (YYYY-MM-DD)
- *duration*: call duration in minutes
- *user_id*: the identifier of the user making the call

**megaline_messages.csv**
- *id*: unique text message identifier
- *message_date*: text message date (YYYY-MM-DD)
- *user_id*: the identifier of the user sending the text

**megaline_internet.csv**
- *id*: unique session identifier
- *mb_used*: the volume of data spent during the session in megabytes
- *session_date*: web session date (YYYY-MM-DD)
- *user_id*: user identifier

**megaline_plans.csv**
- *plan_name*: calling plan name
- *usd_monthly_fee*: monthly charge in US dollars
- *minutes_included*: monthly minute allowance
- *messages_included*: monthly text allowance
- *mb_per_month_included*: data volume allowance in megabytes
- *usd_per_minute*: price per minute after exceeding the package limits (e.g., if the package includes 100 minutes, the 101st minute will be charged)
- *usd_per_message*: price per text after exceeding the package limits
- *usd_per_gb*: price per extra gigabyte of data after exceeding the package limits (1 GB = 1024 megabytes)

## Required Libraries
- pandas
- numpy
- scipy.stats
- matplotlib.pyplot

## Screenshots

![839d3b69-4741-4b37-9594-95d0a1d7469b](https://github.com/adkwn1/statistical_data_analysis/assets/119823114/aa553270-954d-4abf-bbc8-5614996db7ca)
![c5695443-1f1e-422c-8f51-7a203f50d567](https://github.com/adkwn1/statistical_data_analysis/assets/119823114/60b4c4a0-a86e-432b-a257-b9a3be70305f)
