# USA-Financial-Data-Analysis

## Project Overview
This project automates the process of financial data analysis to make it faster and more efficient. The goal is to handle 25 files daily from different regions and create a report by 8 PM.

## Dashboard Link
https://app.powerbi.com/view?r=eyJrIjoiNjA0Y2Q2MDgtMWYyZS00MTgyLTg5ZGMtYTBlOTViZjFlOTk2IiwidCI6Ijg2MDA1ZGZiLWEyZjEtNDdiYy1hNTVkLTkwYmI1MzI0Y2NjYSJ9 

## Problem Statement
Manually sorting, cleaning, transforming, and reporting 25 files every day by 8 PM was inefficient.

## Solution
### To fix this, I automated the entire workflow. Here's how:

Steps Followed:
* Data Collection:

    Used Outlook to gather daily financial data into one folder.

* File Storage:

    used power automate to automatically
  move the file from otlook to a dedicated
  google drive folder



* Data Processing & Cleaning

    Accessed the google drive folder directly
    using power query in power bi.
  
    Cleaned and transformed the data in Power Query.

* Report Generation:

    Created visualizations in Power BI Desktop, including:

        Cards: Average annual income, average monthly balance, average number of payment delays, average credit utilization.

        Charts: Age trends in credit limit adjustment, credit scores across age groups, payment behavior by credit mix, loan distribution, potential  customer age 
  demographics, and more.

## Automated Report Delivery:

Set up an automated process to send the report to clients by 8 PM daily.




## Insights
This project provided several key insights:

### Customer Satisfaction:

    57% of customers are neutral or unsatisfied, while 43% are satisfied.

### Key Metrics:

    Average Annual Income: 167.08k

    Average Monthly Balance: 404.64

    Average Number of Delays in Payment: 21.15

    Average Credit Utilization: 32.25%

### Age-Related Trends in Credit Limit Adjustments:

The average of changed credit limits across different ages shows fluctuations:

    Age 17: 14.1

    Age 20: 9.5

    Age 30: 10.98

    Age 40: 9.24

    Age 45: 9.70

    Age 50: 7.3



### Payment Behavior Trends by Credit Mix:

Payment behavior across different credit mixes:

* Standard:

    High spent, Large value payments: 534

    High spent, Medium value payments: 721

    High spent, Small value payments: 465

    Low spent, Large value payments: 429

    Low spent, Medium value payments: 503

    Low spent, Small value payments: 1046

* Good:

    High spent, Large value payments: 483

    High spent, Medium value payments: 519

    High spent, Small value payments: 344

    Low spent, Large value payments: 239

    Low spent, Medium value payments: 350

    Low spent, Small value payments: 532


* Above Standard:

    High spent, Large value payments: 313

    High spent, Medium value payments: 393

    High spent, Small value payments: 276

    Low spent, Large value payments: 223

    Low spent, Medium value payments: 341

    Low spent, Small value payments: 541

* Bad:

    High spent, Large value payments: 218

    High spent, Medium value payments: 347

    High spent, Small value payments: 248

    Low spent, Large value payments: 249

    Low spent, Medium value payments: 287

    Low spent, Small value payments: 678



## Demographic Insights:

    Most customers are from the '25-50' age group (52.44%)

    Majority of customers travel for business (69.06%)

# **Conclusion**
This project shows how automation can make data workflows faster and more accurate. It reduced manual work and improved reporting efficiency.

    Feel free to explore the dashboard and connect for more information!
