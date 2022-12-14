# Credit_Risk_Analysis

## Overview

In this module, we want to use machine learning to predict if a customer's credit application is high risk or low risk to predict if the application will be approved. We will use several different algorithms (oversampling, undersampling, combinational of over- and undersampling and two models that reduce bias) to help us predict the credit risk. Based off of these models, we hope to recommend one of them to the lending services to use in the future.  

## Results of Different algorithms:

### Naive Random Oversampling:
      Balanced Accuracy Score: 0.66
            
      Precision/Recall:
         High Risk:
            Precision: 0.01
            Recall: 0.72
         Low Risk:
            Precision: 1.00
            Recall: 0.60
          
 ![this is an image](https://github.com/eneubauer2022/Credit_Risk_Analysis/blob/main/Images/NRO.png)
 
 ### SMOTE Oversampling:
       Balanced Accuracy Score: 0.69
       
       Precision/Recall: 
          High Risk:
            Precision: 0.01
            Recall: 0.63
          Low Risk:
            Precision: 1.00
            Recall: 0.68
            
  ![this is an image](https://github.com/eneubauer2022/Credit_Risk_Analysis/blob/main/Images/SMOTE.png)
  
  ### Cluster Centriods Undersampling:
        Balanced Accuracy Score: 0.54
        
        Precision/Recall:
          High Risk:
            Precision: 0.01
            Recall: 0.69
          Low Risk:
            Precision: 1.00
            Recall: 0.40
 
 ![this is an image](https://github.com/eneubauer2022/Credit_Risk_Analysis/blob/main/Images/cc.png)
    
    
   ## SMOTEENN (Over and Under Sampling)
      Balanced Accuracy Score: 0.64
        Precision/Recall:
          High Risk:
            Precision: 0.01
            Recall: 0.70
          Low Risk:
            Precision: 1.00
            Recall: 0.58
            
![this is an image](https://github.com/eneubauer2022/Credit_Risk_Analysis/blob/main/Images/SMOTEEN.png)
          
## Balanced Random Forest Classifier
      Balanced Accuracy Score: 0.79
        Precision/Recall:
          High Risk: 
            Precision: 0.03
            Recall: 0.70
          Low Risk:
            Precision: 1.00
            Recall: 0.87
            
            
![this is an image](https://github.com/eneubauer2022/Credit_Risk_Analysis/blob/main/Images/brfc.png)
          
## Easy Ensemble Classifier
      Balanced Accuracy Score: 0.93
        Precision/Recall:
          High Risk: 
            Precision: 0.09
            Recall: 0.92
          Low Risk:
            Precision: 1.00
            Recall: 0.94
            
 ![this is an image](https://github.com/eneubauer2022/Credit_Risk_Analysis/blob/main/Images/easy.png)
 
 
 ## Summary
 
 Out of all the models, the Easy Ensemble Classifier model would be my recommendation. This model had a very impressive accuracy score of 93%. 
