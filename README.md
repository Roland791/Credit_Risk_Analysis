# Credit_Risk_Analysis

Overview

This analysis seeks to create a supervised machine learning model that can accurately predict credit risk based on data from LendingClub. To complete this analysis, 6 different methods were utilized:

1.	Random Oversampling
2.	SMOTE Oversampling
3.	Cluster Centroid Undersampling
4.	SMOTEENN Sampling
5.	Balanced Random Forest Classifying
6.	Easy Ensemble Classifying

For each method, data was split into training and testing datasets. Accuracy scores, confusion matrices, and classification report results were compiled for each sampling.
Results

Random Oversampling

    •	Accuracy Score: 66.6%

    •	Precision High Risk: 1%

    •	Precision Low Risk: 100%

    •	Recall High Risk: 70%

    •	Recall Low Risk: 63%
 

SMOTE Oversampling

    •	Accuracy Score: 65.7%

    •	Precision High Risk: 1%

    •	Precision Low Risk: 100%

    •	Recall High Risk: 63%

    •	Recall Low Risk: 68%
 
Cluster Centroid Undersampling

    •	Accuracy Score: 65.6%

    •	Precision High Risk: 1%

    •	Precision Low Risk: 100%

    •	Recall High Risk: 69%

    •	Recall Low Risk: 40%
 
SMOTEENN Sampling

    •	Accuracy Score: 54.5%

    •	Precision High Risk: 1%

    •	Precision Low Risk: 100%

    •	Recall High Risk: 72%

    •	Recall Low Risk: 57%
 
Balanced Random Forest Classifying

    •	Accuracy Score: 64.8%

    •	Precision High Risk: 56%

    •	Precision Low Risk: 100%

    •	Recall High Risk: 30%

    •	Recall Low Risk: 100%
 
Easy Ensemble Classifying

    •	Accuracy Score: 92.3%

    •	Precision High Risk: 6%

    •	Precision Low Risk: 100%

    •	Recall High Risk: 91%

    •	Recall Low Risk: 94%


Summary
There are 3 main criteria that can help determine which model is most effective at identifying good loan candidates. 
  1)	Percentage of High-Risk Loans properly classified

    •	Easy Ensemble Classifying – 91%

    •	SMOTEENN Sampling – 72%

    •	Random Oversampling – 70%

    •	Cluster Centroid Undersampling – 69%

    •	SMOTE Oversampling – 63%

    •	Balanced Random Forest Classifying – 30%

  2)	Percentage of Low-Risk Loans properly classified

    •	Balanced Random Forest Classifying – 100%

    •	Easy Ensemble Classifying – 94%

    •	SMOTE Oversampling – 68%

    •	SMOTEENN Sampling – 57%

    •	Random Oversampling – 63%

    •	Cluster Centroid Undersampling – 40%

  3)	Overall accuracy of the model

    •	Easy Ensemble Classifying – 92.3%

    •	Random Oversampling – 66.6%

    •	SMOTE Oversampling – 65.7%

    •	Cluster Centroid Undersampling – 65.6%

    •	Balanced Random Forest Classifying – 64.8%

    •	SMOTEENN Sampling – 54.5%

When analyzing all three factors, Easy Ensemble classification is clearly the most consistent option for modeling. Both the overall accuracy and the Recall measure for high-risk loans are at the top of the group, while the Recall Measure for Low-Risk loans is second of the group. While Balanced Random Forest does outperform in the Low-Risk category, making it overall less accurate. 
