# Analysis of the Bank Marketing Data Set

We are working with a dataset from a Portuguese bank.  The data categorizes direct marketing efforts (phone calls) designed to sell term deposit products.  The [dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) was donated to UCI's Machine Learning Repository. The goal is to predict which contacts are most likely to subscribe to a term deposit. Data range from May 2008 to November 2010

## Analysis

- Break data into training and test sets

- Build a few two-stage logistical regression model: propensity to answer, followed by likliehood to purchase a term loan given that the person answers.

- Build a random forest model

- Test the models against each other and pick the best model

- Build a tool to model the distribution of expected purchase outcomes given different target parameters and given a choice of model

- Establish cutoffs for "worth it" (% of called who purchase) and identify which groups are worth targeting given these cutoffs *and* given a minimum sample size (i.e. you can reach out to lower answering groups with higher yield percentages if the sample size is large enough to justify)

## Application

- Build an application that proposes lists of customers to call given cutoffs from the first area, plus inputs related to exogenous factors (CPI, Euribor, etc.)

## LearnR

- Overview of project
- Literature Review
- Justification of Methodology
    - Logistic Regression
    - Random Forest
    - Which works better?
- Implementation in R
- Similar projects


