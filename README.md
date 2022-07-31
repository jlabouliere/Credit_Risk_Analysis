# Credit_Risk_Analysis
## Overview
Using the credit card credit dataset from LendingClub, an assessment of the LoanStats_2019Q1 dataset is requested.  Six methodologies/algorithms employed:

* Naive Random Oversampling
* SMOTE Oversampling
* Cluster Centroids Undersampling
* SMOTEEN Combination Sampling
* Balanced Random Forest Classifier
* Easy Ensemble Classifier

Each method to be trained and fit before producing balanced accuracy, precision and recall scores.  Subsequently, evaluate the models to determine if any model should be recommended.

## Results

### Naive Random Oversampling

* Balanced Accuracy Score: 64.98%
* Precision
  * High Risk:  .01 (Low precision)
  * Low Risk:   1.00 (High precision
* Recall Score
  * High Risk:  .62
  * Low Risk:   .68  
* ![Screen Shot 2022-07-31 at 3 59 25 PM](https://user-images.githubusercontent.com/98665941/182045143-f7fb5390-dd95-425c-b91d-da384439c247.png)

### SMOTE Oversampling

* Balanced Accuracy Score: 64.44%
* Precision
  * High Risk:  .01 (Low precision)
  * Low Risk:   1.00 (High precision
* Recall Score
  * High Risk:  .63
  * Low Risk:   .66  
*![Screen Shot 2022-07-31 at 4 06 07 PM](https://user-images.githubusercontent.com/98665941/182045328-60fbc668-08dc-42f1-b95d-d804925a11b0.png)

### Cluster Centroids Undersampling

* Balanced Accuracy Score: 64.44%
* Precision
  * High Risk:  .01 (Low precision)
  * Low Risk:   1.00 (High precision
* Recall Score
  * High Risk:  .63
  * Low Risk:   .66  
*![Screen Shot 2022-07-31 at 4 08 03 PM](https://user-images.githubusercontent.com/98665941/182045393-31535a2a-af96-4f8c-91f4-5f3fc8a1cd0d.png)

### SMOTEEN Combination Sampling

* Balanced Accuracy Score: 64.44%
* Precision
  * High Risk:  .01 (Low precision)
  * Low Risk:   1.00 (High precision
* Recall Score
  * High Risk:  .63
  * Low Risk:   .66  
*![Screen Shot 2022-07-31 at 4 10 45 PM](https://user-images.githubusercontent.com/98665941/182045520-9b3bd9d4-bde8-4e86-9853-1f4ee8516733.png)

### Balanced Random Forest Classifier

* Balanced Accuracy Score: 78.78%
* Precision
  * High Risk:  .04 (Low precision)
  * Low Risk:   1.00 (High precision
* Recall Score
  * High Risk:  .67
  * Low Risk:   .91  
*![Screen Shot 2022-07-31 at 4 33 12 PM](https://user-images.githubusercontent.com/98665941/182046210-31181f6e-7bff-4264-a34d-3db4334c8693.png)

### Easy Ensemble Classifier

* Balanced Accuracy Score: 92.54%
* Precision
  * High Risk:  .07 (Low precision)
  * Low Risk:   1.00 (High precision
* Recall Score
  * High Risk:  .91
  * Low Risk:   .94  
*![Screen Shot 2022-07-31 at 4 35 13 PM](https://user-images.githubusercontent.com/98665941/182046273-322878db-ee2b-4aa5-ad9a-6e4138dbd871.png)

## Summary

Utilizing supervised machine learning to assess credit risk with the six algorithms revealed a clear top performing model in the Easy Ensemble Classifier with Balanced Accuracy score of 92.54% and Recalls in the 90s as well.  Precision across all models averaged 99%, but the Easy Ensemble returned a higher Precision level for High Risk entrants at 7%.  Viewing all six models together, it becomes evident that the added strength of the Ensemble methodologies makes them preferrable to Logistic Regression with Resampling to assess credit risk.  Finally, would recommend that any model would benefit from dropping a number of features from the analysis to improve performance and accuracy.  Many features had zero importance and many of the lower ranked features could be reevaluated for inclusion in the models.
