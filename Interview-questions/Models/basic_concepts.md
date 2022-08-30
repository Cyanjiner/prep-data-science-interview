# Basic conceptual questions about data science models

## General model explanations

### What are the `feature vectors`?

    A feature vector is an n-dimensional vector of numerical features that represent an object. In machine learning, feature vectors are used to represent numeric or symbolic characteristics of an object in a mathematical way that's easy to analyze.

### Describe mutivariate data

### Ex

### Explain  `Box Cox transformation`
    A box cox transformation is a statistical method to convert non-normal dependent variables into a regular shape. Also, applying the box cox transformation indicates that you can run a more comprehensive number of bias.

## Decision trees
### What are the steps in making a `decision tree`?

    1. Take the entire data set input
    2. Look for a split that maximizes the separation of the classes. A split is any test that divides data into two sets
    3. Apply the split to the input data (divide step)
    4. Re-apply steps one and two to the divided data
    5. Stop when you meet any stop criteria
    6. This step is called `prunning`. Clean up the tree if you went too far doing splits.

## Regression
### What is `logistic regression`?

    Logistic regression a technique used to forecast the binary outcome from a linear combination of predictor variables.

### What are the drawbacks of the linear model?
    - The assumption of linearity of the errors.
    - It can't be used for count outcomes or binary outcome.s
    - There are overfitting problems that it can't solve.

### What are confounding variables?
    These are extraneous variables in a statistical model that correlates directly or inversely with both the dependent and the independent variable. The estimate fails to account for the confounding factor.

## Naive Bayes
### What is `Naive Bayes Classifier model`?
    Naive Bayes Classifier is a probabilistic model. This design operates on the Bayes theorem principle. The exactness of Naive Bayes can be improved by blending it with other kernel purposes of creating a perfect Classifier.

## Recommender Systems
### What are `recommender systems`?

    Recommender systems are a subclass of information filtering systems that are meant to predict the preferences or ratings a user would give to a product.

### What is `collaborative filtering`?

    Most recommender system uses this filtering process to find patterns and information by collaborating perspectives, numerous data sources, and several agents.


### Explain cross-validation

    Cross-validation is a model validation technique for evaluating how the outcome of a statistical analysis will generalize to an independent data set. It is mainly used in backgrounds where the objective to forecast and one wants to estimate how accurately a model will accomplish in practice.

    The goal of cross-validation is to term a data set to test the model in the training phrase (i.e. validation data set) to limit problems like overfitting and gain insight into how the model will generalize to an independent data set.

## A/B Testing

### What is the goal of A/B Testing?

    This is a statistical hypothesis testing for randomized experiments with two variables. A and B. The objective of A/B testing is to detect any changes to a web page to maximize or increase the outcome of a strategy.

### Do gradient descent methods always converge to similar points?

    No. Because in some cases, they reach a local minima or a local optima point. You would not reach the global optima point. This is governed by the data and the starting conditions.

### What is `root cause analysis`?

    Root cause analysis was initially developed to analyze industrial accidents but is now widely used in other areas. It is a problem-solving technique for isolating the root cause of faults or problems. A factor is called a root cause if its deduction from the problem-fault-sequence averts the final undesirable event from recurring.

### What is a `star schema`?
    It is a traditional database schema with a central table. Satelight tables map IDs to physical names or descriptions and can't be connected to the central fact table using the ID fields