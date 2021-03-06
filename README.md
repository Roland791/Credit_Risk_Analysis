# Credit_Risk_Analysis

## Overview

This analysis seeks to create a supervised machine learning model that can accurately predict credit risk based on data from LendingClub. To complete this analysis, 6 different methods were utilized:

1.	Random Oversampling
2.	SMOTE Oversampling
3.	Cluster Centroid Undersampling
4.	SMOTEENN Sampling
5.	Balanced Random Forest Classifying
6.	Easy Ensemble Classifying

For each method, data was split into training and testing datasets. Accuracy scores, confusion matrices, and classification report results were compiled for each sampling.
Results

### Naive Random Oversampling

    - Accuracy Score: 66.6%
    - Precision High Risk: 1%
    - Precision Low Risk: 100%
    - Recall High Risk: 70%
    - Recall Low Risk: 63%
 
 ![Figure 1](https://github.com/Roland791/Credit_Risk_Analysis/blob/main/Images/Figure%201%20-%20Naive%20Random%20Oversampling.png?raw=true)
 

### SMOTE Oversampling

    • Accuracy Score: 65.7%
    • Precision High Risk: 1%
    • Precision Low Risk: 100%
    • Recall High Risk: 63%
    • Recall Low Risk: 68%
    
 ![Figure 2](https://github.com/Roland791/Credit_Risk_Analysis/blob/main/Images/Figure%202%20-%20SMOTE%20Oversampling.png?raw=true)    
 
### Cluster Centroid Undersampling

    • Accuracy Score: 65.6%
    • Precision High Risk: 1%
    • Precision Low Risk: 100%
    • Recall High Risk: 69%
    • Recall Low Risk: 40%
    
 ![Figure 3](https://github.com/Roland791/Credit_Risk_Analysis/blob/main/Images/Figure%203%20-%20Cluster%20Centroid%20Undersampling.png?raw=true)    
 
### SMOTEENN Sampling

    • Accuracy Score: 54.5%
    • Precision High Risk: 1%
    • Precision Low Risk: 100%
    • Recall High Risk: 72%
    • Recall Low Risk: 57%
 
 ![Figure 4](https://github.com/Roland791/Credit_Risk_Analysis/blob/main/Images/Figure%204%20-%20SMOTEENN%20Sampling.png?raw=true)     
 
### Balanced Random Forest Classifying

    • Accuracy Score: 64.8%
    • Precision High Risk: 56%
    • Precision Low Risk: 100%
    • Recall High Risk: 30%
    • Recall Low Risk: 100%
    
 ![Figure 5](https://github.com/Roland791/Credit_Risk_Analysis/blob/main/Images/Figure%205%20-%20Balanced%20Random%20Forest%20Sampling.png?raw=true)        
 
### Easy Ensemble Classifying

    • Accuracy Score: 92.3%
    • Precision High Risk: 6%
    • Precision Low Risk: 100%
    • Recall High Risk: 91%
    • Recall Low Risk: 94%
    
 ![Figure 6](https://github.com/Roland791/Credit_Risk_Analysis/blob/main/Images/Figure%206%20-%20Easy%20Ensemble%20Analysis.png?raw=true)  


## Summary
There are 3 main criteria that can help determine which model is most effective at identifying good loan candidates. 
  1)	Percentage of High-Risk Loans properly classified

    • Easy Ensemble Classifying – 91%
    • SMOTEENN Sampling – 72%
    • Random Oversampling – 70%
    • Cluster Centroid Undersampling – 69%
    • SMOTE Oversampling – 63%
    • Balanced Random Forest Classifying – 30%

  2)	Percentage of Low-Risk Loans properly classified

    • Balanced Random Forest Classifying – 100%
    • Easy Ensemble Classifying – 94%
    • SMOTE Oversampling – 68%
    • SMOTEENN Sampling – 57%
    • Random Oversampling – 63%
    • Cluster Centroid Undersampling – 40%

  3)	Overall accuracy of the model

    • Easy Ensemble Classifying – 92.3%
    • Random Oversampling – 66.6%
    • SMOTE Oversampling – 65.7%
    • Cluster Centroid Undersampling – 65.6%
    • Balanced Random Forest Classifying – 64.8%
    • SMOTEENN Sampling – 54.5%

When analyzing all three factors, Easy Ensemble classification is clearly the most consistent option for modeling. Both the overall accuracy and the Recall measure for high-risk loans are at the top of the group, while the Recall Measure for Low-Risk loans is second of the group. While Balanced Random Forest does outperform in the Low-Risk category, making it overall less accurate. 
