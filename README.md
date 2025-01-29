# Billing_maximization
Despite increasing efficiency in the legal services industry, billing optimization and realization have remained a problem. There is less time spent on travel (and overall delays) and attorneys are given more convenient ways to meet with their clients. One might expect an increase in efficiency to lead towards increase in profits, but that has not necessarily been the case. Most firms turn towards increasing billable hours and rates to increase profits, but this can have major setbacks. If firms can’t increase the hours per month of their lawyers and the rising price of new layers is unpalatable, how are firms to increase revenue? This project focuses on answering this question.

For this project, we are focusing on the employees, their billing rates, and their average hours. We are going to randomly pull a small subset of billable employees, and allocate them across a set of jobs based on their billing data. All of this will work within our utilization and allocation constraints, where we attempt to work within the desired and expected hours of our employee sample.

Two objective were identified and formulated as below:
1. To maximize the profit by multiplying the profit per hour per class (Pi,k) by the assigned number of hours to the employee (i).
Pni=1 Ppj=1 Pck=1 Xi,j,kPi,k - [Maximize Profit]
2. To maximize the average ratio of billable/non billable hours by multiplying the ratio per employee per class by the number of hours assigned to the employee(i) and dividing by the total number of hours (2059).
(Pni=1 Ppj=1 Pck=1 Xi,j,kRi,k)/2059 - [Maximize Billing Ratio]
