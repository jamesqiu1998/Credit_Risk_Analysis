# Credit_Risk_Analysis
## Overview
Apply Machine learning to sole a real world problem: Credit Card Risk. Using imbalanced-learn and scikit-learn to libraries to build and evaluate models using resampling. (RandomOversampler, SMOTE, ClusterCentroids, SMOTEENN, EasyEnsembleClassifier, BalancedRandomForestClassifier)

## Results
Below list the six different machine learning models and bulletin shows the Balanced Accuravy scores, Confusion Matrix, and the Imbalanced classification Report. 
  - **Naive Random Oversampling (RandomOversampler)**

<img width="909" alt="image" src="https://user-images.githubusercontent.com/104419959/210852332-149e74bf-778e-4feb-918a-a6d95d22f1b3.png">

  - **SMOTE Oversampling(SMOTE)**
  
  <img width="950" alt="image" src="https://user-images.githubusercontent.com/104419959/210852429-fec38599-f3db-4b5c-845f-947a62790f0b.png">

  - **Undersampling (ClusterCentroids)**
  
  <img width="920" alt="image" src="https://user-images.githubusercontent.com/104419959/210852536-ad24507e-e4b1-4ccd-8a09-46fe961ce626.png">

  - **Combination(Over and Under) Sampling (SMOTEENN)**
  
  <img width="944" alt="image" src="https://user-images.githubusercontent.com/104419959/210852642-85eeb432-7a0f-474d-aafe-43407ff6ce23.png">

  - **Balanced Random Forest Classifier (BalancedRandomForestClassifier)**
  
  <img width="900" alt="image" src="https://user-images.githubusercontent.com/104419959/210852755-53fea0ac-bfb5-427b-b4e5-6c964aafdb03.png">

  - **Easy Ensemble AdaBoost Classifier (EasyEnsembleClassifier)**
  
  <img width="932" alt="image" src="https://user-images.githubusercontent.com/104419959/210852860-a5445057-48ee-43bf-9d91-52b8ee5e81ac.png">

## Summary
Upon review of all six resampling models, AdaBoost Classifier was able to have the highest precision for high risk at 9%, and recall at 92%. Comparing to the rest of the test models, this might be the most suitable one to utilize. 
