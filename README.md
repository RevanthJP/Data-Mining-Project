# Data-Mining-Project


PROBLEM 1


EXECUTIVE SUMMARY

A leading bank wants to develop a customer segmentation to give promotional offers to its customers. They collected a sample that summarizes the activities of users during the past few months. You are given the task to identify the segments based on credit card usage.

INRODUCTION

In this first problem, we have taken various steps in order to categorize the customers of a bank based on credit card usage and help the marketing team to draft a plan to reach customers in best way possible. We have explored various aspects of the customer data such as spending, advance payment, credit limit, etc using data exploration techniques such as univariate analysis, bivariate analysis, graphical representations. Based on the data exploration results, techniques such as hierarchical clustering, dendrogram and K-means clustering are used to cluster the data. The clustering is checked for accuracy using methods such as elbow curve and silhouette score. Based on the clustering and its accuracy the marketing team can plan according to reach out the customers in specific ways.

DATA DESCRIPTION

•	spending: Amount spent by the customer per month (in 1000s)

•	advance_payments: Amount paid by the customer in advance by cash (in 100s)

•	probability_of_full_payment: Probability of payment done in full by the customer to the bank

•	current_balance: Balance amount left in the account to make purchases (in 1000s)

•	credit_limit: Limit of the amount in credit card (10000s)

•	min_payment_amt : minimum paid by the customer while making payments for purchases made monthly (in 100s)

•	max_spent_in_single_shopping: Maximum amount spent in one purchase (in 1000s)


PROBLEM 2



EXECUTIVE SUMMARY

An Insurance firm providing tour insurance is facing higher claim frequency. The management decides to collect data from the past few years. You are assigned the task to make a model which predicts the claim status and provide recommendations to management. Use CART, RF & ANN and compare the models' performances in train and test sets.

INRODUCTION

The main intent of this exercise is to the dataset provided by the Insurance company and figure out what is the reason behind the higher claim frequency. In order provide solution to the insurance company for the higher claim frequency or to find out if there are any fraudulent claims being made models have been build to predict using various techniques. Decision tree classifier, Random Forest classifier and Artificial Neural Networks are the three machine learning models used in this problem. The performance of these models, which are evaluated using techniques such as Confusion Matrix, Classification report, Accuracy of the model, ROC curve and ROC_AUC score. Based on the evaluation, the best performing model can be selected and used for solving the problem and providing recommendations.

DATA DESCRIPTION

1. Target: Claim Status (Claimed)
2. Agency Code: Code of tour firm of each firm
3. Type: There are two types of tour insurance firms namely – Airlines and Travel Agency
4. Channel: Contains the details Distribution channel of tour insurance agencies – Online and Offline
5. Product Name: Name of the tour insurance products - Customised Plan, Cancellation Plan, Gold plan, silver plan and bronze plan.
6. Duration: Duration of the tour in days
7. Destination: Destination of the tour
8. Sales: Amount worth of sales per customer in procuring tour insurance policies in rupees (in 100’s)
9. Commission: The commission received for tour insurance firm (Commission is in percentage of sales)
10.Age: Age of insured



