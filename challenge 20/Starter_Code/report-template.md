# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

After observing the modeling results, I determined that the secondary logistic regression model trained with resampled data performed significantly better than the first model trained with original data, especially with predicting high-risk loans ('1'). The model produced higher precision, recall, and f1 scores for high-risk loans, which is most important to aid the lending company in reducing the amount of bad loans and financial losses incurred. Obviously I recommend model 2 using logictic regression trained with resampled data for this credit risk analysis since the accuracy has improved the outcomes when compared to the first model. The results show that it can better assess a higher difference when comparing healthy loan applications to high-risk loan applications, and avoid making loans that will lead to greater loss in the future.
