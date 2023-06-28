## Analysis of user behavior in application
[Link NBVIEWER](https://nbviewer.org/github/evkis/data_analysis_science_pet/blob/main/06_analysis_of_user_behavior_in_application/06_analysis_of_users_behavior_in_app_en.ipynb)

### Description

Analysis of users' behavior of food sale mobile application. based on user logs and A/A/B experiment results (font changes throughout the application)

### Keywords

internet services, marketing analysis, product analysis,EDA, descriptive statistics, funnel, A/A/B-test, statistical hypotheses, z-score, Bonferroni correction

### Stack

python, pandas, numpy, matplotlib, seaborn, SciPy,Plotly

### Input Data 

logs of mobile app (file logs_exp.csv)

EventName — event name;
DeviceIDHash — unique user indentificator;
EventTimestamp — time of action;
ExpId — experiment group number: 246 и 247 — control groups, а 248 — experiment group.

### Conclusion

Sales funnel was built, the users' path to purchase was researched .
The results of the A/B test for the introduction of new fonts was analyzed. 2 control groups was compared with each
other, it was made sure that the traffic was divided correctly, and then compared it with the test group
It was revealed that the new font will not significantly affect user behavior.
