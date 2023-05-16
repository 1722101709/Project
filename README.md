# Project

### Description

In this project we built classification models for low-resource language like Tamil, Kannada, 
Malayalam with both KL-NF techique and BERT for finding offensiveness in a sentence. We developed 
language independent model that can work for any language and for small and large datasets. 
We used datasets of 3 languages to train and test the model. After training the model, we have 
tested the model and compared the results of both KL-NF and BERT. The comparison among 
the accuracy shows that BERT model beat KL-NF in multi-lingual classification of 
offensiveness. The accuracy for BERT model is 82.7% whereas for KL-NF model is 82.5%. 

# RESULTS

## KL-NF Technique 

### Loss Curve
![Loss Curve](Results/KL-NF/LossCurve.png)

### Confusion Matrix
![Confusion Matrix](Results/KL-NF/ConfusionMatrix.png)

### Model Performance

![Model Performance](Results/KL-NF/ModelPerformance.png)


### ROC Curve
![ROC-Curve](Results/KL-NF/ROC-Curve.png)


### TP, TN, FP, FN for each label
![TP, TN, FP, FN for each label](Results/KL-NF/TP-TN-FP-FN-For-Each-Label.png)



## BERT

### Loss Curve for BERT model
![Loss Curve for BERT model](Results/BERT/LossCurve.png)

### Confusion Matrix
![Confusion Matrix](Results/BERT/Confusion%20Matrix.png)

### Model Performance

![Model Performance](Results/BERT/ModelPerformance.png)


### ROC Curve
![ROC-Curve](Results/BERT/ROC-Curve.png)

### TP, TN, FP, FN for each label
![TP, TN, FP, FN for each label](Results/BERT/TP-TN-FP-FN-For-Each-Label.png)


