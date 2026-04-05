🩺 Diabetes Prediction using Machine Learning

📌 Overview

This project predicts the likelihood of diabetes using machine learning models. It demonstrates a complete ML workflow including data preprocessing, feature engineering, model training, and evaluation.
📂 Dataset

The dataset used is the Pima Indians Diabetes Dataset, which contains medical attributes of patients.

Features:
	•	Pregnancies
  
	•	Glucose
  
	•	BloodPressure
  
	•	SkinThickness
  
	•	Insulin
  
	•	BMI
  
	•	DiabetesPedigreeFunction
  
	•	Age
  

Target:
	•	Outcome
	•	0 → No Diabetes
	•	1 → Diabetes

⸻

⚙️ Data Preprocessing
	•	Handled missing values
  
	•	Replaced 0 values (in Glucose, BMI, Insulin, etc.) with NaN
  
	•	Filled missing values using median
  
	•	Feature scaling applied using StandardScaler
  
	•	Train-test split: 80% training / 20% testing
  
🤖 Models Used


1. Logistic Regression
   
	•	Baseline linear model

	•	Performed best on this dataset


3. Support Vector Machine (SVM)

	•	Tested with polynomial kernel

	•	Used for non-linear classification


5. K-Nearest Neighbors (KNN)
   
	•	Distance-based model

	•	Tested multiple values of K


7. Polynomial Logistic Regression
   
	•	Used PolynomialFeatures to capture non-linear relationships

	•	Did not significantly improve performance



📊 Model Evaluation

	•	Evaluation metric: Accuracy Score
  
	•	Models compared
  
	•	Logistic Regression
  
	•	Polynomial Logistic Regression
  
	•	SVM
  
	•	KNN



🔍 Key Insights:

	•	Logistic Regression performed best
  
	•	Dataset is mostly linearly separable
  
	•	Polynomial features did not improve performance
  
	•	Proper preprocessing improved accuracy

