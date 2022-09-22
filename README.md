# Credit Risk Analysis

## Overview

An analysis was performed on credit risk using machine learning in jupyter notebook. Different sampling techniques were used and compared to determine which algorithms tested would be best suited to create to model recommended to determine credit risk. The methods used were Naive Random Oversampling, SMOTE, Cluster Centroids, SMOTEENN, Balanced Random Forest Classifier and Easy Ensemble Classifier. 

## Results

### Naive Random Oversampling

![naive.PNG](https://github.com/mcwatts88/Credit_Risk_Analysis/blob/main/Resources/naive.PNG)

* Balanced Accuracy Score: 65%
* Precision Score:
    * High Risk: 1%
    * Low Risk: 100%
* Recall Score:
    * High Score: 62%
    * Low Score: 68%


### SMOTE

![SMOTE.PNG](https://github.com/mcwatts88/Credit_Risk_Analysis/blob/main/Resources/SMOTE.PNG)

* Balanced Accuracy Score: 62%
* Precision Score:
    * High Risk: 1%
    * Low Risk: 100%
* Recall Score:
    * High Score: 59%
    * Low Score: 66%


### Cluster Centroids

![CC.PNG](https://github.com/mcwatts88/Credit_Risk_Analysis/blob/main/Resources/CC.PNG)

* Balanced Accuracy Score: 50%
* Precision Score:
    * High Risk: 1%
    * Low Risk: 100%
* Recall Score:
    * High Score: 59%
    * Low Score: 43%


### SMOTEENN

![SMOTEENN.PNG](https://github.com/mcwatts88/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.PNG)

* Balanced Accuracy Score: 62%
* Precision Score:
    * High Risk: 1%
    * Low Risk: 100%
* Recall Score:
    * High Score: 71%
    * Low Score: 53%


### Balanced Random Forest Classifier

![brf.PNG](https://github.com/mcwatts88/Credit_Risk_Analysis/blob/main/Resources/brf.PNG)

* Balanced Accuracy Score: 78%
* Precision Score:
    * High Risk: 4%
    * Low Risk: 100%
* Recall Score:
    * High Score: 67%
    * Low Score: 91%


### Easy Ensemble Classifier

![eec.PNG](https://github.com/mcwatts88/Credit_Risk_Analysis/blob/main/Resources/eec.PNG)

* Balanced Accuracy Score: 93%
* Precision Score:
    * High Risk: 7%
    * Low Risk: 100%
* Recall Score:
    * High Score: 91%
    * Low Score: 94%


## Summary

The model recommended is the Easy Ensemble Classifier due to having a 93% accuracy score. While none of the models had a great score for high risk, easy ensemble was the best. It had the highest precision scores, recall scores and balanced accuracy scores of the models.