## A/B test analysis for an online shop
[Link]()

### Description

Using the data of the online shop it is necessary to prioritize hypotheses, to evaluate the results of A/B testing with various methods and calculate various cumulative metrics.

### Keywords

internet services, marketing analysis, product analysis,EDA, descriptive statistics, ICE, RICE, cumulative metrics, statistical hypotheses, A/B test, Mann-Whitney test

### Stack

python, pandas, numpy, matplotlib, seaborn, SciPy

### Input Data 

- list of hypotheses (hypothesis.csv file)

Hypothesis — a brief description of the hypothesis;

Reach — user coverage 10-point scale;

Impact — impact on users 10-point scale;

Confidence — confidence in the hypothesis 10-point scale;

Efforts — the cost of resources to test the hypothesis 10-point scale.

- information about user orders in the online store (orders.csv file.)

TransactionID - order ID;

visitorID — ID of the user who made the order;

date — the date when the order was made;

revenue — order revenue;

group — the A/B test group that the order fell into.

- information about user visits to the online store (visitors.csv file)

date - date;

group — A/B test group;

visitors — the number of users on the specified date in the specified A/B test group.

### Conclusion

The prioritization of hypotheses on the ICE and RICE frameworks has been carried out. Then I analyzed
the results of the A/B test, plotted cumulative revenue, average receipt,
conversions by groups, and then calculated the statistical significance of differences in conversions
and average receipts based on raw and clean data. 
