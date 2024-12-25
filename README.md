# heart-disease-prediction
A project for heart disease prediction using machine learning
# ❤️ Heart Disease Prediction

## 📖 Project Overview
This repository contains a machine learning project aimed at predicting heart disease using the UCI Heart Disease dataset. The project explores various classification models to determine the most effective one for early diagnosis.

## 🛠️ Methodology
1. **Data Preprocessing**: 
   - Handled outliers, null values, and duplicates.
   - Standardized numerical features.
   - Balanced categorical data for better performance.
   
2. **Feature Selection**:
   - Key features: Age, Sex, Chest Pain Type, ST Slope, and Resting Blood Pressure.
   - Used data visualization and correlation analysis to identify important features.

3. **Model Training**:
   - Trained multiple machine learning models: Logistic Regression, SVM, Decision Tree, and Random Forest.
   - Evaluated models using metrics like accuracy, precision, recall, and AUC-ROC.

## 📂 Dataset Description
The dataset includes 918 samples and 11 attributes:
- **Age**: Patient's age (numerical).
- **Sex**: Patient's gender (categorical: M/F).
- **ChestPainType**: Types of chest pain (categorical: ATA, NAP, ASY, TA).
- **RestingBP**: Resting blood pressure (numerical).
- **Cholesterol**: Cholesterol level (numerical).
- **FastingBS**: Fasting blood sugar (categorical: 0 or 1).
- **RestingECG**: Resting ECG results (categorical: Normal, ST, LVH).
- **MaxHR**: Maximum heart rate achieved (numerical).
- **ExerciseAngina**: Exercise-induced angina (categorical: Y/N).
- **Oldpeak**: ST depression induced by exercise (numerical).
- **ST-Slope**: Slope of the ST segment (categorical: Up, Flat, Down).

## 📊 Model Results
- **Logistic Regression**:
  - **Accuracy**: 88%
  - **AUC-ROC**: 0.93
- **Random Forest**:
  - **Accuracy**: 83.4%
- **Decision Tree**:
  - **Accuracy**: Lower than Logistic Regression and Random Forest.

## 📚 References
- UCI Heart Disease Dataset on [Kaggle](https://www.kaggle.com/)
- Libraries: Scikit-learn, Pandas, Matplotlib
