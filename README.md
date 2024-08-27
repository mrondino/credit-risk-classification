# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to evaluate models based on loan risk and determine how well the regression model predicts both the healthy loans and high-risk loans. 
* The data is about financial historical lending information from a peer-to-peer lending service, and I am using it to predict if loans have a risk of defaulting. 
* I am trying to predict 'loan status' which is either healthy (0) or at risk (1).
* I did the model-fit-predict steps by modeling the data and splitting out the field we were looking against, fitting it to the training data, and predicting the risk level.
* I used LogisticRegression and assigned a random state of 1 to it. 
  

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Description of Model 1 Accuracy:
    The accuracy score is .99 which means that the percentage of correctly predicted instances to the total instances in the dataset was very high. 
* Precision:
    The Precision score is 1.00 for '0' and .86 for '1'. This means the accuracy of the positive predictions was greater for '0' than '1'.
* Recall scores:
  The Recall score is .99 for '0' and .95 for '1'. This means that the model found all positive samples better for the '0' model than the '1' model. 
## Summary

The predicitions for the '0' (healthy loans) are better, but the overall model is very high in general. 
* The model for predicting the '0' (healthy loans) has a higher precision and recall. 
* Since there is a difference in precision with the '0' and '1', I would say that the performance depends on this. It seems more important to predict the '1's, so I would be cautious with this. I would not recommend the model to predict high-risk loans.
