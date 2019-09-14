# Fraud Detection with or without Oversampling 99.3% ROC_AUU_SCORE
Best : Using_SMOTE_OVERSAMPLING Extra Trees Classifer :  Validation Accuracy: 99.3%, ROC_AUC_Score: 99.3%
        it can be further improved by decreasing the fraud_threhold(currently at 100)

## Fraud_Detection_Using_SMOTE_OVERSAMPLING.ipynb

I am able to achieve the following accuracies in the validation data. These results can be further improved by reducing the 
parameter, number of frauds used to create features from category items. I have used a threshold of 100.

* Logistic Regression : 
        Validation Accuracy: 68.2%, ROC_AUC_Score: 68.2%
                
* Random Forest : 
        Validation Accuracy: 98.9%, ROC_AUC_Score: 98.2%
                
* Linear Support Vector Machine : 
        Validation Accuracy: 53.8%, ROC_AUC_Score: 53.9%
                
* K Nearest Neighbors : 
        Validation Accuracy: 87.1%, ROC_AUC_Score: 87.1%
                
* Extra Trees Classifer : 
        Validation Accuracy: 99.3%, ROC_AUC_Score: 99.3%


