# costomer-churn-model

# Business problem
Business problem is very simple, There is a Bank who wants to retain their existing customers who may churn, for that they have to know which existing customers has the highest probability of leaving the company.

# Constraints
1.Low Latency(In Real time within in few nano seconds the model should be able to classify that Costomer will leave bank or not )

2.Errors can be very costly, customer can leave bank immediately.

3.Interpretablity is important.

4.Probablity of a particular customer belonging to each class is needed.

# Machine Learning Formulation

So Converting a Business problem to a Machine Learning problem, This seems to be a simple binary classification problem in which we have 2 classes, "yes" and "no".

We have some numerical features, some categorical features.

# Data

We have 10000 rows with 13 features and 1 target variable, Every row tells us different customer details and whether they churned or not after 2 months of observation.

# PERFORMANCE METRICS
It is a simple classification problem.

Other than that we will use accuracy(after checking if data is balanced or not), here the important thing is we care equally about Precision and Recall because we care equally about False Positives and False Negatives.
