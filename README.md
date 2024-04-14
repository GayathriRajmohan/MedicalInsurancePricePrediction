# Medical Insurance Price Prediction
## Medical Insurance Price Prediction using Machine Learning – Python
Design and implement a machine learning (ML) solution to accurately predict the prices of medical insurance premiums for individuals based on their demographic, lifestyle, and health-related characteristics. The primary objective is to develop a robust model that leverages historical insurance data to forecast insurance costs with high precision and reliability.

## Objective
The model should incorporate features such as age, gender, BMI, smoking status, pre-existing conditions, geographic location, and family medical history to generate personalized insurance premium estimates. The proposed ML system aims to assist insurance companies in optimizing pricing strategies, enhancing risk assessment processes, and providing more transparent and fair insurance premiums to customers.
## Steps:
# 1.Importing Libraries and Dataset
Loaded the medical insurance dataset containing information about 1338 data points with 6 independent features and 1 target feature (charges).Conducted exploratory data analysis (EDA) to understand relationships between different features and the target variable.
## 2.Exploratory Data Analysis
EDA is an approach to analyzing the data using visual techniques. It is used to discover trends, and patterns, or to check assumptions with the help of statistical summaries and graphical representations. While performing the EDA of this dataset we will try to look at what is the relation between the independent features that is how one affects the other.
## 3.DATA PREPROCESSING
Data preprocessing is technique to clean the unusual data like the missing values,wrong data,wrong format of data,duplicated data and the outliers.
a. Checked for and handled duplicates in the dataset.

b. Identified and treated outliers in the BMI column using the IQR method.

c. Explored the distribution of continuous data in the age and BMI columns.

d. Encoded discrete categorical data (sex, BMI, region) for model prediction.
## 4.Model Development:
a. Explored multiple machine learning models (Linear Regression, SVR, Random Forest Regressor, Gradient Boosting Regressor, XGBoost Regressor).

b. Utilized cross-validation and grid search for hyperparameter tuning.

c. Identified XGBoost as the best-performing model based on evaluation metrics.
## 5.Feature Importence
In order to determine which features had the greatest influence on predictions, the final XGBoost model's feature importances were examined.

![Image](https://github.com/GayathriRajmohan/MedicalInsurancePricePrediction/blob/main/op/op.jpg)
## 6.Final Model:
a. Train the final XGBoost model with optimized hyperparameters.

b. Dropp less important features to simplify the model.
## 7.Prediction on data
Demonstrate how the trained model to predict medical insurance charges for new data.
## 8.Conclusion
Out of all the models XGBoost model is giving the highest accuracy this means predictions made by this model are close to the real values as compared to the other model.so that it provides most effective for predicting medical insurance charges based on the given dataset.
