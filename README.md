# Practical Application Assignment III: Comparing Classifiers

## Overview: 
This repository contains a data analysis performed by Marco A. Godoy as part of the Practical Application Assignment III for the UC Berkeley Professional Certificate in ML/AI Program (2023).

For a link to the Jupyter Notebook, please click here:<br/>
https://github.com/marcoantoniogodoy/ucberkeley-mlai-practical-application-III/blob/main/prompt_III.ipynb

Contact Information:<br/>
https://www.linkedin.com/in/marco-antonio-godoy

## Data:
In this practical application, the goal is to compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. 

The dataset comes from the UCI Machine Learning repository link. The data is from a Portugese banking institution and is a collection of the results of multiple marketing campaigns. We will make use of the article accompanying the dataset here for more information on the data and features.

The dataset contains information from a total of 79,354 contacts obtained from 17 campaigns that took place between May 2008 and November 2010.

The goal of this analysis is to produce a model that can predict if a person contacted by the bank will turn into a deposit. Since there is no need to predict the amount of money that will be deposited, this is mainly a data classification problem.

## Summary of the results obtained from the analysis
As supported by the results of the analysis, we concluded that our optimized LogisticRegression classifier is the best model to predict if a customer will make a deposit. Furthermore, we identified that macroeconomic data such as Employment Variation rate, Consumer Price Index, Euribor 3 month rate are among the most important features when modeling the classifier. As it comes to duration, even though it was also rated as a highly influential feature for the outcome of the target variable, a warning was provided by the authors of the dataset indicating that caution must be taken when creating predictive models due to ambiguity of this feature. For that reason, through the optimization process we made sure to provide alternative models were the duration duration feature was not set.

## Next steps and Recommendations:
As it is pointed out in the detailed analysis, results were inconclusive when attempting to optimize the Decision Tree classifier with a GridSearch, as well as the inability to optmize the SVC classifier due to computing limitations. Therefore, it may be advisable to perform further optimizations to this analysis as increased computing resources become available.
