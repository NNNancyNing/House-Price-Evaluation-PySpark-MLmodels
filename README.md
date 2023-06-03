# House-Price-Evaluation-PySpark-MLmodels
 
## 1. Project Context

- **Kaggle Source**:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

- **Overall Description**:
Used creative feature engineering methods, 
and advanced machine learning models, 
to accurately predict each house price in Ames based on multiple numerical and categorical house features.

- **Language & Environment**: 
The project was coded with PySpark on Databricks.           

 ## 2. Data Description

- **Training data**: 
1460 observations, 80 features describing physical, geographical and selling characteristics of individual houses, together with 1 outcome variable showing the true sale price. 

Feature examples:
<img src="https://github.com/NNNancyNing/House-Price-Evaluation-PySpark-MLmodels/blob/main/Image1.png" width="500" height="400"/>

- **Testing data**: 
contains 1459 observations and 80 same features as the train set.

 ## 3. Feature Engineering & Models Training

- **Feature Engineering Steps**: 
missing values solution; label encoding; adding in customized features
      
- **Model Training**:  
building model pipeline(OneHotEncoder, StringIndexer, VectorAssembler, CrossValidator); 
Training models: Linear Regression, XGBoost, Random Forest, GBT

- Well-tuned XGBoost gave the best performance on test set.
