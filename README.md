# Heart_Disease_Prediction

Objective:
The primary goal of this project is to develop a predictive model for heart disease diagnosis based on various patient health indicators. The model aims to assist medical professionals in identifying individuals at risk of heart disease, thus enabling timely and effective medical interventions.

Data Description:
The dataset consists of various health-related attributes for patients, which include:

Age: Age of the patient.
Sex: Gender of the patient (1 = male; 0 = female).
CP (Chest Pain Type): Indicates the type of chest pain experienced by the patient (1 to 4).
Trestbps (Resting Blood Pressure): The patient's resting blood pressure (in mm Hg).
Chol (Serum Cholesterol): Serum cholesterol level in mg/dl.
FBS (Fasting Blood Sugar): Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
Restecg (Resting Electrocardiographic Results): Results of the resting electrocardiogram (0, 1, 2).
Thalach (Maximum Heart Rate Achieved): Maximum heart rate achieved during the test.
Exang (Exercise Induced Angina): Exercise-induced angina (1 = yes; 0 = no).
Oldpeak: ST depression induced by exercise relative to rest.
Slope: The slope of the peak exercise ST segment (0, 1, 2).
CA (Number of Major Vessels Colored by Fluoroscopy): Number of major vessels (0-3).
Thal: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect).
Target: Diagnosis of heart disease (1 = presence of heart disease; 0 = absence of heart disease).
Methodology:

Data Preprocessing:

Cleaning the dataset to handle any missing or inconsistent data.
Normalizing or standardizing numerical values for better model performance.
Encoding categorical variables where necessary.

Exploratory Data Analysis (EDA):
Analyzing the distribution and relationship of each feature with the target variable.
Visualizing data through graphs and plots to identify patterns and correlations.

Model Development:

Splitting the dataset into training and testing sets.
Implementing various machine learning algorithms such as Logistic Regression, Decision Trees and Random Forest.

Model Evaluation:

Using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC to evaluate model performance.
Comparing the results of different algorithms to select the best-performing model.

Outcomes and Conclusion:
The Random Forest model outperformed the Logistic Regression and Decision Tree models across all evaluation metrics, achieving the highest accuracy, precision, recall, and F1-score.

The model demonstrated superior performance with an accuracy of 84.62%, precision of 87.23%, recall of 83.67%, and F1-score of 85.42%, outperforming both the Decision Tree model (76.92% accuracy, 78.00% precision, 79.59% recall, 78.79% F1-score) and the Logistic Regression model (65.93% accuracy, 68.75% precision, 67.35% recall, 68.04% F1-score), thereby establishing itself as the most effective algorithm for heart disease prediction in this study.
