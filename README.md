# Credit Risk Analysis

## Overview of the Analysis
- In this challenge we will use Python and machine learning models to help evaluate credit risk. RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier are the machine learning algorithms to achieve this analysis.

## Results
- Balanced accuracy score, precision and recall scores of Random Over Sampler model
<p align="center">
    <img src="https://raw.githubusercontent.com/davidbaek90/Credit_Risk_Analysis/main/Resources/RandomOverSampler.PNG">
</p>

- Balanced accuracy score, precision and recall scores of SMOTE model
<p align="center">
    <img src="https://raw.githubusercontent.com/davidbaek90/Credit_Risk_Analysis/main/Resources/SMOTE.PNG">
</p>

- Balanced accuracy score, precision and recall scores of Cluster Centroids model
<p align="center">
    <img src="https://raw.githubusercontent.com/davidbaek90/Credit_Risk_Analysis/main/Resources/cluster.PNG">
</p>

- Balanced accuracy score, precision and recall scores of SMOTEENN model
<p align="center">
    <img src="https://raw.githubusercontent.com/davidbaek90/Credit_Risk_Analysis/main/Resources/SMOTEEN.PNG">
</p>

- Balanced accuracy score, precision and recall scores of Baalanced Random Forest Classifier model
<p align="center">
    <img src="https://raw.githubusercontent.com/davidbaek90/Credit_Risk_Analysis/main/Resources/BRFC.PNG">
</p>

- Balanced accuracy score, precision and recall scores of Easy Ensemble Classifier model
<p align="center">
    <img src="https://raw.githubusercontent.com/davidbaek90/Credit_Risk_Analysis/main/Resources/EasyEnsemble.PNG">
</p>

## Summary
- Out of the six models, the EasyEnsembleClassifier has the highest balanced accuracy score of 93.2%. EasyEnsembleClassifier also has the highest precision (9%) and highest recall (92%), and F1 of 16%.
- By giving highest accuracy, precision, recall and F1 score, I would recommend EasyEnsembleClassifier model to be adopted for this analysis.
