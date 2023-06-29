## A/B-test correctness analysis evaluation for an online shop_en
[Link NBVIEWER]()

### Description

The task is to evaluate the results of the A/B test. There is a dataset with user actions, technical task and several auxiliary datasets.

### Keywords

internet services, marketing analysis, product analysis,EDA, descriptive statistics, 
funnel, A/B-test, statistical hypotheses, z-score, Bonferroni correction

### Stack

python, pandas, numpy, matplotlib, seaborn, SciPy,Plotly

### Input Data 

datasets/ab_project_marketing_events.csv — calendar of marketing events for 2020;

/datasets/final_ab_new_users.csv — all users who registered in the online store in the period from December 7 to December 21, 2020;

/datasets/final_ab_events.csv — all events of new users in the period from December 7, 2020 to January 4, 2021;

/datasets/final_ab_participants.csv — table of test participants.

### Conclusion

The test was carried out incorrectly in time and data collection was carried out with errors. 
Nevertheless test analysis could be performed while the perceived effect of the change will be equal to 8% about.
The number of events per day of Group B does not change as dramatically as Group A.
The median number of events in group A per user is 6, and for group B - 4.
Group A behaves better compared to B in terms of conversion.
A/B test analysis results
Group A shows a better conversion rate than group B statistically significantly only for the product page. At the same time, the "sensitivity" of such a test is very low. New recommendation system have not made conversion better.
As a result of incorrect organization of the test, most of the data was lost and test lost its "sensitivity" to changes 
It would me recommended to perform this test again.
