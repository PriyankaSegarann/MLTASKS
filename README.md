MACHINE LEARNING TASK

COLAB LINK: 
https://colab.research.google.com/drive/1NwtoZCTz_6yu-9wFhPCrWuQt0oUWaDPK?usp=sharing

1.CLASSIFICATION:

Heart Disease Dataset UCI

INSPIRATION OF THE PROJECT:

       This project primarily revolves around the critical need to improve early diagnosis, prevention, and management of heart disease, which is one of the leading causes of death globally.
       
ABOUT DATASET (METADATA):

      The Heart Disease dataset from the UCI Machine Learning Repository is a widely used dataset for training and evaluating machine learning models in the field of healthcare.The Heart Disease dataset from UCI serves as a crucial resource for advancing machine learning applications in healthcare. Its inspiration stems from the need to enhance early detection, improve diagnostic accuracy, and contribute to the overall betterment of cardiovascular health management. By leveraging this dataset, researchers and practitioners can develop innovative solutions that potentially save lives and improve the quality of life for many individuals.
      
DATASET LINK: 
https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci

CONTENTS:
COLUMN DESCRIPTION:

Age: Age of the patient in years.
Sex: Gender of the patient (1 = male; 0 = female).
CP (Chest Pain Type):
0: Typical angina
1: Atypical angina
2: Non-anginal pain
3: Asymptomatic
Trestbps (Resting Blood Pressure): Resting blood pressure in mm Hg on admission to the hospital.
Chol (Serum Cholesterol): Serum cholesterol in mg/dl.
Fbs (Fasting Blood Sugar > 120 mg/dl): (1 = true; 0 = false)
Restecg (Resting Electrocardiographic Results):
0: Normal
1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
Thalach (Maximum Heart Rate Achieved): Maximum heart rate achieved during the stress test.
Exang (Exercise Induced Angina): Exercise-induced angina (1 = yes; 0 = no).
Oldpeak: ST depression induced by exercise relative to rest.
Slope: The slope of the peak exercise ST segment:
0: Upsloping
1: Flat
2: Downsloping
Ca (Number of Major Vessels Colored by Fluoroscopy): Number of major vessels (0-3) colored by fluoroscopy.
Thal: A blood disorder called thalassemia:
1: Normal
2: Fixed defect
3: Reversible defect
Target: Diagnosis of heart disease (angiographic disease status):
0: No heart disease
1: Heart disease present

OBJECTIVE:
          The objective of the Heart Disease dataset from the UCI Machine Learning Repository is to predict whether a patient has heart disease based on various biomedical attributes. This dataset is commonly used for machine learning and statistical modeling tasks to develop predictive models.
                
CLASSIFICATION MODELS:

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Decision Tree
Random Forest
XGBoost
Gradient Boosting
AdaBoost

RESULTS:

The minimum age to have a heart disease start from 28 years old.
Most of the males and females get  heart disease at the age of 58 to 59 years.
Male percentage i the data: 69.56%
Female percentage in the data : 30.44%
Males are 128.53% more than female in the data.
Chest pain types and their count includes
        1.Typical angina 497 2.Non-anginal pain 284 3.Atypical angina 167 4.Asymptomatic 77
        
Best model - DECISION TREE CLASSIFIER 

The Decision Tree Classifier has:
A very high cross-validation accuracy of 99.46%.
A high test accuracy of 97.09%.


2..REGRESSION:

SUPERMARKET SALES DATASET

INSPIRATION OF THE PROJECT:

The inspiration behind projects that use the Supermarket Sales Dataset typically revolves around several key objectives:
Data Analysis and Insights: 
Business Strategy Improvement:
Customer Segmentation
Predictive Analytics
Operational Efficiency

ABOUT DATASET (METADATA):
The Supermarket Sales Dataset is a valuable resource for analyzing various aspects of retail operations and consumer behavior. This dataset typically includes transactional data from a supermarket, detailing individual sales transactions with various attributes that provide a comprehensive view of the supermarket's operations.
DATASET:https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

CONTENTS:

COLUMN DESCRIPTION:
Invoice ID: Unique identifier for each transaction.
Branch: Branch identifier (e.g., A, B, C).
City: City where the branch is located.
Customer Type: Type of customer (e.g., Member, Normal).
Gender: Gender of the customer.
Product Line: Category of products sold (e.g., Health and beauty, Electronic accessories).
Unit Price: Price per unit of product.
Quantity: Number of units sold.
Tax: Tax amount for the sale.
Total: Total amount (including tax) for the sale.
Date: Date of the transaction.
Time: Time of the transaction.
Payment: Payment method (e.g., Cash, Credit card, Ewallet).
COGS: Cost of goods sold.
Gross Margin Percentage: Gross margin percentage.
Gross Income: Gross income from the sale.
Rating: Customer rating of the service.
REGRESSION MODELS:
1.Linear Regression
2.Decision Tree Regression 
3.Random Forest Regression 
4.Gradient Boosting Regression
5.Ridge Regression
6.Lasso Regression
7.Elastic-net Regression

RESULT:

Analysis:
MSE and MAE: Lower values are better. 
R-squared (R2): Higher values closer to 1 are better.

Here are the performance metrics for each model:
Linear Regression
MSE: 8.48010568987929e-07 MAE: 0.0007091416588265531 R2: 0.9999999999869655
Decision Tree Regression
MSE: 3.8599847999999977 MAE: 1.2122249999999999 R2: 0.9999406694781063
Random Forest Regression
MSE: 1.7552136199105683 MAE: 0.7489308749999921 R2: 0.9999730212046161
Gradient Boosting Regression
MSE: 5.1709995358350564 MAE: 1.693296886272827 R2: 0.9999205183136541
Lasso Regression
MSE: 2.0600231421633876e-05 MAE: 0.0037228250744092504 R2: 0.9999999996833608
Ridge Regression
MSE: 3.1784960563442814e-09 MAE: 4.384754124422408e-05 R2: 0.9999999999999512
Elastic Net Regression
MSE: 2.164271483601558e-05 MAE: 0.0038158601480911703 R2: 0.9999999996673371

CONCLUSION:
1.Ridge Regression has the lowest MSE (3.1784960563442814e-09) compared to all    other models, indicating it makes predictions that are extremely close to the actual values. 2.Ridge Regression has the lowest MAE (4.384754124422408e-05), further supporting the observation that the predictions are very accurate. 
3.Ridge Regression has the highest R2 value (0.9999999999999512), indicating it explains almost all the variability in the target variable.
