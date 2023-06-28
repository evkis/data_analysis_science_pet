## Mobile application profit loss analysis
[Link](https://github.com/evkis/data_analysis_science_pet/blob/main/04_mobile_application_loss_analysis/04_application_profit_loss_analysis_en.ipynb)

### Description

Based on the data it is necessary to answer following questions:
• users' location and operation system they use
• costs of attraction of users from various advertising channels
• users'revenue
• factors that prevent attracting the users

### Keywords

internet services, marketing analysis, EDA, descriptive statistics, unit economics, LTV, ROI, retention, conversion, users profile, cohort analysis, CAC, lifetime

### Stack

python, pandas, numpy,matplotlib

### Input Data 

Data on users attracted from May 1 to October 27, 2019:

server log with data about users' visits (visits_info_short.csv file): User Id, Region, Device, Channel, Session Start, Session End;

purchases for the period (file orders_info_short.csv): User Id, Event Dt — event date, Revenue;

advertising expenses (file costs_info_short.csv): Channel — identification of the advertising source,Dt — date of the advertising campaign, Costs — costs of advertising campaign.

### Conclusion

The data from app was analyzed.
Various metrics were calculated, cohort analysis was used: LTV, CAC, Retention rate, DAU, WAU, MAU, etc. Previously written metric calculation functions were used. 
conclusions have been drawn based on the data obtained.
