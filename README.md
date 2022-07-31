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

