# Credit_Risk_Analysis

### The purpose of this analysis is to determine what the best way to test and train our data to correctly predict credit risk.
---
## *RandomOversampler*

1. Balanced Accuracy Score
    * The score for this algorithim is 0.6365290015349844
    * This means the model was only accurate 63.7% of the time
    
2. Recall Score
    * The score for this algorithim is 0.66
    * This means it had a large number of false negatives
    
---

## *ClusterCentroids*

1. Balanced Accuracy Score
    * The score for this algorithim is 0.5104477642006195
    * This means the model was only accurate 51% of the time
    
2. Recall Score
    * The score for this algorithim is 0.44
    * This means it had a very large number of false negatives


---

## *SMOTE*

1. Balanced Accuracy Score
    * The score for this algorithim is 0.6460662500856127
    * This means the model was only accurate 64.6% of the time
    
2. Recall Score
    * The score for this algorithim is 0.66
    * This means it had a large number of false negatives
    

---

## *SMOTEENN*

1. Balanced Accuracy Score
    * The score for this algorithim is 0.6375241226214794
    * This means the model was only accurate 63.7% of the time
    
2. Recall Score
    * The score for this algorithim is 0.57
    * This means it had a very large number of false negatives


---

## *BalancedRandomForestClassifier*

1. Balanced Accuracy Score
    * The score for this algorithim is 0.7833859095688749
    * This means the model was accurate 78% of the time
    
2. Recall Score
    * The score for this algorithim is 0.90
    * This means it had a very small number of false negatives


---

## *EasyEnsembleClassifier*

1. Balanced Accuracy Score
    * The score for this algorithim is 0.9256318213133181
    * This means the model was accurate 92.6% of the time
    
2. Recall Score
    * The score for this algorithim is 0.94
    * This means it had a very small number of false negatives

---

## *Conclusion*
The best algorithim for this dataset is the EasyEnsembleClassifier model. The justification for using this algorithim is the high accuracy score of 94% and the low false negatives. This means more customers will be approved and will make more money for the company.
