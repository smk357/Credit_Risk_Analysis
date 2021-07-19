# Credit_Risk_Analysis

### An analysis of machine learning models used to predict credit risk

## Overview

The purpose of this analysis was to use 6 different machine learning models (RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier,  and EasyEnsembleClassifier) to predict credit risk (divided into "low risk" and "high risk") based on large number of criteria. Models were imported, trained, and the accuracy, precision, and recall metrics were determined and tabulated.

## Results

- Results from Random Oversampling:

![image](https://user-images.githubusercontent.com/79061124/126086575-ed866678-cd61-41db-983c-8a3697c60465.png)

- Results from SMOTE:

![image](https://user-images.githubusercontent.com/79061124/126086609-ce9fa27a-e190-45b3-a155-51fd43cfebe6.png)

- Results from ClusterCentroids:

![image](https://user-images.githubusercontent.com/79061124/126086676-d74b4438-ccc9-4d25-844a-f4f9507f7f6e.png)

- Results from SMOTEENN:

![image](https://user-images.githubusercontent.com/79061124/126086702-7ce56814-9659-477a-b838-c7e2f7a04301.png)

- Results from BalancedRandomForestClassifier:

![image](https://user-images.githubusercontent.com/79061124/126086736-7d4b1bcf-2f00-46a4-bc68-ee4f1efb05d6.png)

- Results from EasyEnsembleClassifier:

![image](https://user-images.githubusercontent.com/79061124/126086761-ed8bbf76-95cd-4790-9068-89b98f8ceddc.png)

## Summary

The first 4 models (RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN) used showed comparable results for accuracy/precision/recall. The final 2 BalancedRandomForestClassifier,  and EasyEnsembleClassifier showed improved results for accuracy/precision/recall. 

Of all the models, the recommended one would be Easy Ensemble AdaBoost Classifier, showing particularly impressive results: over 93% balanced accuracy, low risk precision and recall of 1.00 and 0.94 respectively, and a high risk recall of 0.92. Unfortuantely, all models had unacceptably low scores for high risk precision, indicating a strong tendency towards generating false positives.
