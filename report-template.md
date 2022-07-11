# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
*Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. You want to use various techniques to train and evaluate models with imbalanced classes.  You will use a dataset of historical lending activity from peer to peer lending servies to build a model that can identify the credit worthiness of borrowers.

* Explain what financial information the data was on, and what you needed to predict.
This project used the file lending_data.csv to predict credit worthiness based on several attributes.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
We checked the balance of variable "y" based on the value_counts function.
* Describe the stages of the machine learning process you went through as part of this analysis.
The stages were at first using a regression model with the orignina data.  Then using a Resression Model with resampled training data we then used a RandomOverSampler module to have the model better perform.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
The methods performed were a train test split and then fitting the model and then predicting the model.  After than we performed a RandomOverSamper model to have the denied loans have the same weight as the healthy loans.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  *This model is using real data and spliting it into test and training data.  The precision for healthy loans was 100% and recall wall was 99% a strong model for predicting healthy loans.  The risk loans were 85% precision and 91% recall still a strong model but not as strong as the healthy loan model.  Accuracy was 90.24% for this model.



* Machine Learning Model 2:
  * After over sampling the high risk loans the precision was 84% for high risk loans but recall increased to 99%.  The precision and recall was the same for healthy loans. Accuracy was 99.36 for this model.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* I'm going with the over sampled machine learning model 2 due to the fact the accuracy increased and the recall increased for risky loans.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
* Both because the 0's over time will make you money off of interest payments and are a larger sample, however if high risk loans get approved at a lower interest rate they may default and lose the entire investment.

If you do not recommend any of the models, please justify your reasoning.
