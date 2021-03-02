<DIV ALIGN=CENTER>
    <h1>
Home Credit Default Risk Prediction
</h1>
      
</DIV> 

This [presentation slide](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Home%20Credit%20Default%20Risk%20Prediction/Presentation_Slide.pdf) contains data overview, EDA and feature engineering, imbalanced data handling approach, and model building and evaluation.

### **Goal and Objective**<br>
The goal of this project is to make default predictions given certain characteristics of a credit applicant and help loan companies to minimize default risk. 

### **Dataset**<br>
[Home Credit Default Risk] (https://www.kaggle.com/c/home-credit-default-risk/data)

### **[EDA & Feature Engineering](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Home%20Credit%20Default%20Risk%20Prediction/EDA_Feature_Engineering.ipynb)**
- Univariate Analysis
- Bivariate Analysis
- Data Cleaning

### **[Imbalanced Dataset Handing Approach](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Home%20Credit%20Default%20Risk%20Prediction/Imbalanced_Data_Handling.ipynb)**
Adaptive re-sampling
- Oversample minor class (Synthetic Minority Over-sampling Technique - SMOTE)
- Under-sample major class (Random Sampling)

Cost-sensitive learning
- Loss function of the classification algorithm is modified to weight the classification errors differently for major and minor class
- Misclassification cost adds to the loss function

### **Model Building**
- [Support Vector Machine](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Home%20Credit%20Default%20Risk%20Prediction/Model%20Fitting/SVM.ipynb)
- [Random Forest](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Home%20Credit%20Default%20Risk%20Prediction/Model%20Fitting/RandomForest.ipynb)
- [XGBoost](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Home%20Credit%20Default%20Risk%20Prediction/Model%20Fitting/XGBoost.ipynb)
- [ANN](https://github.com/amilyhuang10/MSCA_Projects/blob/main/Home%20Credit%20Default%20Risk%20Prediction/Model%20Fitting/ANN_Regression.ipynb)

### **Model Comparison**
- AUC 
- Recall
