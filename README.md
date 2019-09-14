# Fraud_Detection
Fraud Detection with or without Oversampling

# Fraud_Detection_Using_SMOTE_OVERSAMPLING

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


Fraud_Detection_Without_Oversampling

I am able to achieve the following accuracies in the validation data. but ROC_AUC_SCORE is not acceptable. Using over-sampling technique improved results substantially. These results can be further improved by reducing the parameter, number of frauds used to create features from category items. Currently, I have used a threshold of 100.

    Logistic Regression :

      Validation Accuracy: 96.4%, ROC_AUC_Score: 50.2%

    Random Forest :

      Validation Accuracy: 97.8%, ROC_AUC_Score: 70.9%

    Linear Support Vector Machine :

      Validation Accuracy: 96.4%, ROC_AUC_Score: 50.3%

    K Nearest Neighbors :

      Validation Accuracy: 96.4%, ROC_AUC_Score: 50.6%

    Extra Trees Classifer :

      Validation Accuracy: 98.0%, ROC_AUC_Score: 78.7%


