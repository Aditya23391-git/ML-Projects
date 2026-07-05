# Heart Disease Prediction using Machine Learning

## Project Overview

This project focuses on analyzing patient health data and building machine learning models to predict the presence of heart disease. The workflow combines **exploratory data analysis, data preprocessing, feature scaling, and classification modeling** to understand patterns in the dataset and evaluate different machine learning algorithms for heart disease prediction.

The project was carried out in Python using a healthcare dataset containing patient attributes such as age, blood pressure, cholesterol, chest pain type, ECG results, and other medical indicators.

---

## Problem Statement

Heart disease is one of the leading causes of death worldwide, making early prediction and risk assessment extremely important.
The objective of this project is to analyze patient health-related features and build a machine learning model that can predict whether a person is likely to have heart disease.

---

## Objectives

* Explore and understand the structure of the heart disease dataset
* Perform data cleaning and preprocessing
* Handle invalid / zero values in important health-related columns
* Encode categorical variables into machine-learning-ready format
* Scale numerical features for better model performance
* Train and compare multiple classification models
* Evaluate models using classification metrics such as accuracy and F1-score

---

## Dataset

The project uses a **heart disease dataset** containing patient-level medical and diagnostic information.

### Key Features in the Dataset

* **Age**
* **Sex**
* **ChestPainType**
* **RestingBP**
* **Cholesterol**
* **FastingBS**
* **RestingECG**
* **MaxHR**
* **ExerciseAngina**
* **Oldpeak**
* **ST_Slope**

### Target Variable

* **HeartDisease** → indicates whether the patient has heart disease or not

---

## Tools & Libraries Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **scikit-learn**

---

## Project Workflow

### 1. Data Loading and Inspection

* Loaded the heart disease dataset using Pandas
* Checked column names, shape, data types, and dataset information
* Reviewed summary statistics and duplicate values

### 2. Exploratory Data Analysis

Exploratory analysis was performed to understand the distribution of medical variables and their relationship with heart disease.
The notebook includes visual analysis of features such as:

* Age
* Resting Blood Pressure
* Cholesterol
* Maximum Heart Rate
* Sex
* Chest Pain Type
* Fasting Blood Sugar
* Heart Disease distribution

Visualizations such as **bar charts, histograms, count plots, box plots, violin plots, and heatmaps** were used to study the data.

### 3. Data Cleaning

Basic preprocessing and cleaning steps were applied, including:

* checking duplicate records
* replacing zero values in important health columns such as **Cholesterol** and **RestingBP**
* using mean-based replacement for invalid zero values
* reviewing numerical feature distributions before and after cleaning

### 4. Data Preprocessing

To prepare the dataset for machine learning:

* categorical variables were converted using **one-hot encoding**
* the dataset was transformed into numeric format
* selected numerical features were scaled using **StandardScaler**

### 5. Train-Test Split

The dataset was split into **training and testing sets** using `train_test_split` to evaluate model performance on unseen data.

### 6. Model Building

Multiple classification algorithms were trained and compared, including:

* **Logistic Regression**
* **K-Nearest Neighbors (KNN)**
* **Naive Bayes**
* **Decision Tree Classifier**
* **Support Vector Machine (SVM)**

### 7. Model Evaluation

The models were evaluated using:

* **Accuracy Score**
* **F1 Score**
* **Confusion Matrix**
* **Classification Report**

This helped compare model performance and assess how well each model predicted heart disease.

---

## Machine Learning Models Used

| Model                        | Purpose                           |
| ---------------------------- | --------------------------------- |
| Logistic Regression          | Baseline classification model     |
| K-Nearest Neighbors (KNN)    | Distance-based classification     |
| Naive Bayes                  | Probabilistic classifier          |
| Decision Tree                | Tree-based classification model   |
| Support Vector Machine (SVM) | Margin-based classification model |

---

## Key Learning Outcomes

Through this project, I practiced:

* working with healthcare datasets
* performing exploratory data analysis in Python
* handling invalid values in medical data
* encoding categorical variables for machine learning
* scaling numerical features using `StandardScaler`
* training and comparing multiple classification models
* evaluating model performance using common classification metrics

---

## Repository Contents

* **Jupyter Notebook / Python file** containing:

  * data loading
  * data cleaning
  * exploratory data analysis
  * preprocessing
  * model training
  * evaluation

---

## Conclusion

This project demonstrates an end-to-end machine learning workflow for heart disease prediction using Python. By combining **EDA, preprocessing, feature scaling, and classification models**, the project provides a practical understanding of how healthcare data can be used to identify patterns and support predictive analysis.

It also helped strengthen my understanding of **classification problems, preprocessing pipelines, and model evaluation** in a healthcare-focused machine learning project.

