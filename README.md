# 1.Heart-Attack-Prediction Using ML

#  2.Introduction
Cardiovascular diseases, particularly heart attacks, are a leading cause of mortality worldwide. Predicting heart attacks in advance using machine learning can help in early diagnosis and prevention. This project aims to build a Heart Attack Prediction System using Logistic Regression, SVC, Decision Tree, K-Nearest Neighbors (KNN), and Gradient Boosting.

# 3.Problem Statement
How might we develop an ML-based model to predict the likelihood of a heart attack based on patient health parameters, ensuring accurate diagnosis and timely intervention?

# 4.Dataset Information 
#Feature Description
'Age -> Age of the patient (in years)
'Sex	-> Gender (0 = Female, 1 = Male)
ChestPainType	-> Type of chest pain experienced (Typical Angina, Atypical Angina, Non-Anginal, Asymptomatic)
RestingBP	-> Resting blood pressure (in mm Hg)
Cholesterol	-> Serum cholesterol level (in mg/dL)
FastingBS	-> Fasting blood sugar (>120 mg/dL: 1 = True, 0 = False)
RestingECG ->	Resting electrocardiographic results (0 = Normal, 1 = ST-T wave abnormality, 2 = Left ventricular hypertrophy)
MaxHR	-> Maximum heart rate achieved
ExerciseAngina -> Exercise-induced angina (1 = Yes, 0 = No)
Oldpeak	-> ST depression induced by exercise relative to rest
ST_Slope ->	Slope of the peak exercise ST segment (Up, Flat, Down)
HeartDisease -> Target variable (1 = Heart Disease, 0 = No Heart Disease)

# 5.Machine Learning Models Used
compared five different Machine Learning models:
Logistic Regression – For binary classification of heart disease.
Support Vector Machine (SVM) – For better generalization and margin maximization.
Decision Tree – To understand feature importance and model interpretability.
K-Nearest Neighbors (KNN) – A distance-based approach to find similar patient patterns.
Gradient Boosting (GBM) – A powerful ensemble learning method for improved accuracy.

# 6.Model Evaluation Metrics
Multiple metrics to evaluate model performance:
✅ Accuracy
✅ Precision & Recall
✅ F1 Score
✅ ROC-AUC Score

# 7.Results & Observations
Logistic Regression = 84.23%
Support Vector Classifier = 86.5%
Decision Tree Classifier = 82.61%
KNN Model = 84.24%
Gradient Boosting Classifier = 87.50%

- Gradient Boosting performed the best with an accuracy of 87.50%.
- SVC also showed strong performance, while Decision Tree,Logistic Regression and KNN had lower accuracy.

# 8.Conclusion

- Machine Learning can effectively predict heart attacks based on patient data.
- Gradient Boosting and SVC showed the best performance.
- More data and feature engineering could improve model accuracy further.
