# Credit_Risk_Analysis
## Analysis Overview

The purpose of this analysis is to develop a Python programming machine learning model for risk analysis of financial loans. SMOTE and RandomOverSampler algorithims are used to oversample data, and Cluster Centroids algorithim is used to undersample data. SMOTEENN algorithim is used to combine the sampling models. BalancedRandomForestClassifier and EasyEnsembleClassifier reduces bias in the algorithmic data analysis and compares the machine learning models used. 

## Results

- Balanced accuracy score is sixty-five percent. 
- The high_risk prescision is only one percent with an F1 score of two percent.
- The low_risk had a precision rate of one hundred percent with a sixty-eight percent sensitivity. 
![RandomeOverSampler]()

- The balanced accuracy score is sixty-four percent. 
- The high_risk precision is about one percent with sixty-three percent sensitivity which makes a F1 of two percent only. 
![SMOTE]()

- The balanced accuracy score is down to about fifty-two percent. 
- The high_risk is one percent with sixty-three percent sensitivity which makes a F1 of one-percent, and due to the high number of false positives, low_risk sensitivity is only forty percent. 
![ClusterCentroids]()

- The balanced accuracy score is about sixty-two percent. 
- The high_risk prevision is one percent with sixty-eight percent sensitivity with a F1 of two percent. 
- Due to the high number of false positives, the low_risk sensitivity is fifty-sevent percent. 
![SMOTEENN]()

- The balanced accuracy score improved to seventy-nine percent. 
- The high_risk precision is at four percent with sixty-seven percent sensitivity whivh makes a F1 of only seven percent. 
- There are less false positives, the low_risk sensitivity is ninety-one percen with one-hundred percent precision. 
![BalancedRandomForestClassifier]()

- The balanced accuracy score is about ninety-three percent
- The high_risk precision is at seven percent with ninety-one percent sensitivity which makes a F1 of only fourteen percent. 
- With less false positives in the comps, low_risk sensitivity is ninety-four percent with one hundred percent precision. 
![EasyEnsembleClassifier]()

## Summary 

 The majority of six algorithim models used to perform the credit risk analysis show weak precision in determining if a credit risk is high. The EasyEnsembleClassifier model results improved mostly in the sensitivity of the high risk credits. The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. The results that show low precision have a lot of low risk credits that falsely detect a high risk, which would hurt the bank's credit risk. I would not recommend the bank to use any of these models to predict credit risk. 
