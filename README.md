## Heart Disease Prediction using Machine Learning

A machine learning project that predicts the presence of heart disease using patient medical data. The project applies multiple classification algorithms and compares their performance to identify the most effective model.

## Project Overview
Heart disease is one of the leading causes of death worldwide. Early detection can help medical professionals take preventive action and improve patient outcomes.
This project uses machine learning techniques to analyze clinical attributes and predict whether a patient is likely to have heart disease.
The project demonstrates a complete machine learning workflow, including:
Exploratory Data Analysis (EDA)
Feature analysis
Model training
Model comparison
Feature importance analysis

## Objectives

Perform Exploratory Data Analysis (EDA) on the dataset

Identify key features influencing heart disease

Train and compare multiple machine learning models

Evaluate models using performance metrics

Determine the best-performing predictive model

## Dataset

Dataset: Heart Disease Dataset

The dataset contains several medical attributes used to predict heart disease.

Features
Feature	Description
age	Age of the patient
sex	Gender
cp	Chest pain type
trestbps	Resting blood pressure
chol	Cholesterol level
fbs	Fasting blood sugar
restecg	ECG results
thalach	Maximum heart rate achieved
exang	Exercise induced angina
oldpeak	ST depression
slope	ST slope
ca	Number of major vessels
thal	Thallium stress test
Target Variable
Value	Meaning
0	No heart disease
1	Heart disease present

 ## Exploratory Data Analysis

EDA was conducted to understand:
Dataset structure
Feature distributions
Target variable balance
Correlation between features
Visualization techniques used:
Target distribution plots
Correlation heatmaps
Feature importance analysis

## Machine Learning Models Used

The following models were implemented and evaluated:

Logistic Regression
Random Forest
XGBoost
LightGBM
CatBoost

Neural Network (MLP)

## Machine Learning Pipeline
Data Loading
Data Exploration (EDA)
Data Preprocessing
Feature Selection
Train-Test Split
Feature Scaling
Model Training
Model Evaluation
Model Comparison
Model Saving

## Model Performance

Typical performance results:

Model	Accuracy
Logistic Regression	~85%
Random Forest	~88%
XGBoost	~90%
LightGBM	~90%
CatBoost	~91%
Neural Network	~88%

Tree-based boosting models showed the best performance on this dataset.

📂 Project Structure
heart-disease-prediction
│
├── HEART_DISEASE_PREDICTION_MODEL.ipynb
├── heart.csv
├── heart_disease_model.pkl
├── README.md
└── requirements.txt

## Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotli
Seaborn
Scikit-learn
XGBoost
LightGBM
CatBoost
Open and run:
HEART_DISEASE_PREDICTION_MODEL.ipynb

## Model Saving
The trained model can be saved using:
joblib.dump(model, "heart_disease_model.pkl")

## Future Improvements
Hyperparameter tuning
Deep learning approaches
Model deployment with Streamlit
Integration with healthcare systems

## Author

Rohith Yadav G
B.Tech – Artificial Intelligence and Machine Learning
