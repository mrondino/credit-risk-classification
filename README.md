# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
   The purpose of this analysis is to evaluate models based on loan risk and determine how well the regression model predicts both the healthy loans and high-risk loans. 
* Explain what financial information the data was on, and what you needed to predict.
    The data is about financial historical lending information from a peer-to-peer lending service, and I am using it to predict if loans have a risk of defaulting. 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    I am trying to predict 'loan status' which is either healthy (0) or at risk (1).
* Describe the stages of the machine learning process you went through as part of this analysis.
    I did the model-fit-predict steps by modeling the data and splitting out the field we were looking against, fitting it to the training data, and predicting the risk level.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    I used LogisticRegression and assigned a random state of 1 to it. 
  

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Description of Model 1 Accuracy:
    The accuracy score is .99 which means that the percentage of correctly predicted instances to the total instances in the dataset was very high. 
* Precision:
    The Precision score is 1.00 for '0' and .86 for '1'. This means the accuracy of the positive predictions was greater for '0' than '1'.
* Recall scores:
  The Recall score is .99 for '0' and .95 for '1'. This means that the model found all positive samples better for the '0' model than the '1' model. 
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
  The predicitions for the '0' (healthy loans) are better, but the overall model is very high in general. 
* Which one seems to perform best? How do you know it performs best?
  The model for predicting the '0' (healthy loans) has a higher precision and recall. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  Since there is a difference in precision with the '0' and '1', I would say that the performance depends on this. It seems more important to predict the '1's, so I would be cautious with this. 
If you do not recommend any of the models, please justify your reasoning.
  I would not recommend the model to predict high-risk loans.
