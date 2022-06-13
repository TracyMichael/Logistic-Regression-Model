# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis. 

The Purpose of the analysis is to predict a Logistic Regression Model with both original data and resampled data to understand how accurate a model would be.

* Explain what financial information the data was on, and what you needed to predict.

The data is based on loan size, interest rate, borrower income, debt to income, number of accounts, deregatory statements, and total debt.


* Provide basic information about the variables you were trying to predict (e.g., value_counts).

Value_counts: The value counts looks at how many X's there are against the total of Y's.

Shape: Amount of rows vs. columns.


* Describe the stages of the machine learning process you went through as part of this analysis.

Initially I'm cleaning the data set in order to train, test, and split the dataframe.  After that I am creating two Logisitic Regression Models, one of which uses the original data and the other which uses resampled data.  Within this process I am fitting the data and formulating a prediction based on the test data set.  I then measure the accuracy to make sure a large portion of the data is being represented.  At that point I am looking at the confusion matrix to understand the comparison of true and false positives or negatives.  If the number of false positives and negatives are low, the data is more trustworthy.  The classification report uses the ture and false negatives and positives in order to create a ratio of data integrity.  I repeat these steps for the resampled data and compare the two sides to see which is more accurate. 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

I used the following:

LogisticRegression: Creates a model that we will use to fit the data into.  This model is empty which allows for molding with the actual data.

lr_model: In this method we are fitting the data into the LogisticRegression method to make sure the line of best fit is chosen in order to make predicitons.

Predict: Making predictions based on the line of best fit.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
  
The first model was very accurate as it relates to the healthy loans and decently accurate as it relates to the high-risk loans. The precision and recall scores were perfect with a perfect regression. The amount of false negatives and  false positives are decently low.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

The second model was very accurate as it relates to the healthy loans and at a good level of accuracy as it relates to the high-risk loans. The precision and recall scores (sensitivity) were perfect with a perfect regression and the precision score was perfect as it related to high-risk loans and decent as it relates to sensitivity.  The amount of false negatives are very low and the false positives are relatively low.
  

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

I would prefer to use the model with the resampled data because it was more accurate as it relates to the recall scores.  I believe it is more important to predict the 1's because these loans are riskier and would require more accuracy.  These loans have clients that will have historically made decisions that are worse than the healthy client loan group.  I'd like to make sure I'm getting accurate data predictions from the riskier group.

If you do not recommend any of the models, please justify your reasoning.
