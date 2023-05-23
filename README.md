# Fingerhut.com Probability of Purchase Model Code Repository

The aim of this project, in collaboration with industry partner Bluestem Brands Inc., is to give meaningful insights on storefront Fingerhut.com. 

We created a probability of purchase model for each individual customer- testing 4 different machine learning algorithms in doing so. We also performed clustering algorithms- trying to see if visitors to the website could be placed in groups/clusters.

**Below, we list our methods:**

_Feature Selection_

1. Correlation Matrix (through _dython_): Pearson's R, Correlation Ratio, and Cramer's V
3. Extreme Gradient Boost (XG Boost)
4. Principal Component Analysis
5. Mutual Information Score

_Classification Methods - Method of Addressing Class Imbalance_

1. **Logistic Regression** - Class Weights
2. **Random Forest** - Class Weights
3. **K-Nearest Neighbor** (KNN) - Oversampling Majority Class
4. **Convolutional Neural Networks** (CNN) - Oversampling Majority Class

_Metrics Looked Into_

1. Accuracy
2. Sensitivity (TPR)
3. Specificity (TNR)
4. ROC AUC 
5. Precision
6. F-Score

_Clustering Methods_

1. **K Prototype**; Elbow Method: Silhoette Score 
2. **K Means**; Elbow Method

Results, data processing, and data cleaning will not be posted due to a non-disclosure agreement however, this serves as a code repository of the steps & methods we took to perform the analysis. 

Balancing the dataset- due to large ratio of non-purchasing to purchasing vistors to the website was taken into account through different sampling methods. Namely- oversampling (OS) and utilization of class weights (CW). 

