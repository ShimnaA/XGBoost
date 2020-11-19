***Model Selection and Boosting***

    - K-fold CrossValidation
    - Measure in the most relevant way the performance of each of your ML model
    - dataset : Social_Network_Ads
       - of a car company which has just released a brand new Luxury suv
       - Trying to understand through this dataset which customers will buy suvs
       
    - In Kernal SVM model, we apply k-fold crossvalidation, cv=10
    - Train set is divided into 10 parts and in each step one part is taken as test set
    - 10 accuracies are obtained 
    - 90.33% average accuray, 6.57% Standard Deviation
    
***Grid Search***

    - We are tuning the hyperparameter of KernelSVM
    - regularisation parameter C [0.25, 0.5, 0.75,1], kernel {linear, rbf}
    - gamma (for rbf only) [0.1,0.2,0.3,0.4, 0.5,0.6,0.7,0.8,0.9]
    
    - Best Accuracy: 90.67 %
    - Best Parameter  {'C': 0.5, 'gamma': 0.6, 'kernel': 'rbf'}
