## Analysis of user behavior in application based on logs.
[Link]()

### Description

Analysis of the behavior of mobile app (second hand stuff store) users based on logs. 
It is necessary to identify user groups that differ by metrics: retention rate, time spent in the app, frequency of actions, 
conversion to a target action — viewing contacts, conduct EDA, segment users based on actions, test statistical hypotheses.
### Keywords

internet services, marketing analysis, product analysis,EDA, descriptive statistics, funnel, A/B-test, statistical hypotheses, z-score

### Stack

python, pandas, numpy, matplotlib, seaborn, SciPy,Plotly

### Input Data 

application user logs after October 7, 2019 (mobile_dataset.csv file)

event.time — time of the transaction event.name — event name user.id — user ID

dataset with data about the application resource (mobile_sources.csv)

userId — user ID source — the source from which the user installed the application


### Conclusion

Data analysis was performed and following conclusions was made:
retention is approximately the same for all weeks, this is caused by the peculiarity of the application (the second week is about 17 percent, and the third about 8 percent)
a huge number of users spend time scrolling through the tips page and the page with photos,
there is a failure according to the data of October 9-12 and according to unique users from October 7-12,
the median number of user sessions is 8, the session length is 4 minutes, and the session time is 8 minutes,
time in the app increases conversion to target action, conversion to a target action does not depend on the attraction channel,
it's too early to talk about user retention, since a month of data is not enough for this type of goods.
