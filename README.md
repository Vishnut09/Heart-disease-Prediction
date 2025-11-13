# Heart-disease-Prediction
Heart Disease Prediction using Machine Learning
--> Overview :

This project aims to predict the likelihood of heart disease in patients based on medical attributes using Machine Learning.
By leveraging data-driven insights, this model helps in early detection and prevention of cardiovascular diseases.

1) Project Objectives :

Analyze patient health data to identify key risk factors.

Build and evaluate machine learning models for predicting heart disease.

Compare performance of multiple algorithms and select the best performing model.

Provide data visualization and interpretability for better understanding of health indicators.

2) Dataset :

Source: UCI Machine Learning Repository – Heart Disease Dataset

Attributes:

Age

Sex

Chest pain type (cp)

Resting blood pressure (trestbps)

Serum cholesterol (chol)

Fasting blood sugar (fbs)

Resting ECG results (restecg)

Maximum heart rate achieved (thalach)

Exercise induced angina (exang)

ST depression (oldpeak)

Slope of peak exercise ST segment (slope)

Major vessels colored by fluoroscopy (ca)

Thalassemia (thal)

Target (presence or absence of heart disease)

3) Data Preprocessing

Handled missing values

Encoded categorical variables

Scaled numerical features using StandardScaler

Split data into training and testing sets (80:20)


4) Visualizations

Correlation heatmap

Distribution of features

Count plots for categorical attributes

Feature importance ranking


5) Machine Learning Models Used

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Best Model: Random Forest Classifier
Accuracy: ~85% (can vary depending on tuning)

6) Evaluation Metrics

Accuracy Score

Precision, Recall, and F1 Score

Confusion Matrix

ROC Curve & AUC Score


7) Technologies Used

Language: Python 

Libraries:

pandas, numpy, matplotlib, seaborn,scikit-learn
