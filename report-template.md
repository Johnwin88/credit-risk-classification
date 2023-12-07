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
  - Overall Accuracy: 99.2%
  - Healthy loan:
    -  Precision: 99.7%
    -   Recall: 99.5%
  - High-risk loan:
    - Precision: 84.7%
    - Recall: 91.0%



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  - Overall Accuracy: 99.2%
  - Healthy loan:
    -  Precision: 100%
    -   Recall: 99.4%
  - High-risk loan:
    - Precision: 84.1%
    - Recall: 99.04%



## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Both the standard model (Model 1) and the oversampled trained model (Model 2) demonstrate high performance, with over 99% accuracy in identifying low-risk loans and approximately 84% precision in high-risk loan predictions. This indicates a high level of predictive accuracy (precision) across both loan categories for both models, alongside exceptional low-risk loan identification (recall).

The key difference lies in their recall of high-risk loans. Model 1 shows a high recall rate (>90%), while Model 2 excels with a very high rate (>99%). This suggests that Model 2 outperforms Model 1 by about 8% in accurately identifying high-risk loans.

Given the context of this data, Model 2 is considered superior. Its performance remains consistently high across all metrics, except for a notable increase in high-risk loan recall. The ability to identify high-risk loans is crucial in this domain, as these loans present a more significant risk compared to low-risk loans.
