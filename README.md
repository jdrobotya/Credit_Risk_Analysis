# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of this project is to predict a credit card risk by applying machine learning skills. Different techniques will be employed  to train and evaluate models with unbalanced classes. A credit card data set from LendingClub will be used  to predict if the client is likely to have high or low credit risk.  

## Results: 
There were six machine learning models applied  while working on this module. Below you can see the balanced accuracy scores, precision and recall scores  for each of  models: 

### 1) Naive Random Oversampling:

![Screen Shot 2022-09-17 at 4 11 11 PM](https://user-images.githubusercontent.com/103322251/190875739-6bcfb30e-41c6-417f-95de-856471f58f65.png)

Balance accuracy: this model makes accurate prediction  65% of the time
Precision: only 1% of predicted high risk clients are actually high risk, 100% predicted low risk clients are actually low risk
Recall: 62% of high risk clients are classified as high risk and 68% of low risk  clients are classified as low risk.


### 2) SMOTE Oversampling

![Screen Shot 2022-09-17 at 4 18 20 PM](https://user-images.githubusercontent.com/103322251/190875747-b000f193-a4e1-4dbc-8f0a-4489a83947aa.png)

Balance accuracy: this model makes accurate prediction  64.4% of the time
Precision: only 1% of predicted high risk clients are actually high risk, 100% predicted low risk clients are actually low risk
Recall: 63% of high risk clients are classified as high risk and 66% of low risk  clients are classified as low risk.


### 3) Undersampling

![Screen Shot 2022-09-17 at 4 42 16 PM](https://user-images.githubusercontent.com/103322251/190875772-f8c9aaaa-fcf4-4788-b021-174b108eaf7a.png)

Balance accuracy score: this model makes accurate prediction  64.4% of the time
Precision: only 1% of predicted high risk clients are actually high risk, 100% predicted low risk clients are actually low risk
Recall: 60% of high risk clients are classified as high risk and 43% of low risk  clients are classified as low risk.


### 4) Combination (Over and Under) Sampling

![Screen Shot 2022-09-17 at 4 42 27 PM](https://user-images.githubusercontent.com/103322251/190875782-938924fb-7fa2-4c03-8ea7-f6f269b2e282.png)

Balance accuracy score: this model makes accurate prediction  63.7% of the time
Precision: only 1% of predicted high risk clients are actually high risk, 100% predicted low risk clients are actually low risk
Recall: 70% of high risk clients are classified as high risk and 57% of low risk  clients are classified as low risk


### 5) Balanced Random Forest Classifier

![Screen Shot 2022-09-17 at 4 43 22 PM](https://user-images.githubusercontent.com/103322251/190875799-982fb05d-76e7-405e-ba37-dc46d05f3657.png)

Balance accuracy score: this model makes accurate prediction  78.7% of the time
Precision: 4% of predicted high risk clients are actually high risk, 100% predicted low risk clients are actually low risk
Recall: 67% of high risk clients are classified as high risk and 91% of low risk  clients are classified as low risk.


### 6) Easy Ensemble AdaBoost Classifier

![Screen Shot 2022-09-17 at 5 15 06 PM](https://user-images.githubusercontent.com/103322251/190876745-08427445-03ba-4825-b85a-4bae831e8c54.png)

Balance accuracy score: this model makes accurate prediction  92.5% of the time
Precision: 7% of predicted high risk clients are actually high risk, 100% predicted low risk clients are actually low risk
Recall: 91% of high risk clients are classified as high risk and 94% of low risk  clients are classified as low risk.

##Summary: 
By looking at the results of all six modules, it’s safe to say that  Easy Ensemble AdaBoost Classifier is the best model for this data set because it has the highest prediction accuracy and  precision score for high risk clients. The sensitivity of this module is still not perfect,  since it categorizes  a lot of low risk clients as high risk even though they are low risk.  It is safer for the bank to overestimate in this case, then underestimate. 


