# Customer Churn Analysis

## Project Overview

This project focuses on analyzing and predicting customer churn using the **Telco Customer Churn dataset**. The objective was to understand which customer-related factors are associated with churn and to build machine learning models that can classify whether a customer is likely to leave the service.

The project combines **data cleaning, exploratory data analysis, feature preprocessing, and classification modeling** to study churn behavior and compare the performance of multiple machine learning algorithms.

---

## Problem Statement

Customer churn is one of the key challenges for subscription-based businesses such as telecom companies. Losing existing customers directly impacts revenue and increases customer acquisition costs.

The goal of this project is to analyze customer demographics, account details, and service usage patterns to identify factors influencing churn and build a model that can predict whether a customer is likely to churn.

---

## Objectives

* Clean and preprocess the customer churn dataset
* Explore customer behavior and churn patterns using visual analysis
* Convert categorical data into a machine-learning-ready format
* Train and compare multiple classification models
* Evaluate model performance using accuracy, F1-score, confusion matrix, and classification report

---

## Dataset

The project uses the **Telco Customer Churn dataset**, which contains customer-level information such as:

* customer demographics
* tenure
* monthly charges
* total charges
* contract details
* internet services
* payment method
* support and protection services
* churn status

### Target Variable

* **Churn** → whether the customer left the service or not

---

## Tools & Libraries Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **scikit-learn**
* **SciPy**

---

## Project Workflow

### 1. Data Loading and Inspection

* Loaded the Telco churn dataset using Pandas
* Checked dataset shape, column information, and summary statistics
* Inspected missing values and column data types

### 2. Data Cleaning

* Dropped the `customerID` column since it does not contribute to prediction
* Converted `TotalCharges` to numeric format
* Handled invalid / missing values in `TotalCharges`
* Performed basic null-value checks

### 3. Exploratory Data Analysis

Exploratory analysis was performed to study the relationship between churn and customer/service attributes such as:

* gender
* partner / dependents
* internet service
* payment method
* contract type
* online security / backup / tech support
* monthly charges, tenure, and total charges

Visualizations were used to compare churn patterns across different categories and understand customer behavior.

### 4. Data Preprocessing

To prepare the data for machine learning:

* categorical features were encoded using **Label Encoding**
* selected multi-category features were transformed using **One-Hot Encoding**
* numerical features (`tenure`, `MonthlyCharges`, `TotalCharges`) were standardized using **StandardScaler**

### 5. Train-Test Split

The dataset was split into training and testing sets using `train_test_split` with an **80:20 ratio**.

### 6. Model Building

The following machine learning models were trained and compared:

* **Logistic Regression**
* **Decision Tree Classifier**
* **Naive Bayes**
* **K-Nearest Neighbors (KNN)**
* **Support Vector Machine (SVM)**

### 7. Model Evaluation

Model performance was compared using:

* **Accuracy Score**
* **F1 Score**

The best-performing model was then further evaluated using:

* **Confusion Matrix**
* **Classification Report**

---

## Models Used

| Model               | Purpose                                             |
| ------------------- | --------------------------------------------------- |
| Logistic Regression | Baseline linear classification model                |
| Decision Tree       | Tree-based model for non-linear decision boundaries |
| Naive Bayes         | Probabilistic classification approach               |
| KNN                 | Distance-based classification model                 |
| SVM                 | Margin-based classifier for binary classification   |

---

## Evaluation Metrics

The project uses the following evaluation metrics:

* **Accuracy** – overall prediction correctness
* **F1 Score** – balance between precision and recall
* **Confusion Matrix** – breakdown of correct and incorrect predictions
* **Classification Report** – precision, recall, F1-score for each class

---

## Key Learning Outcomes

Through this project, I practiced:

* cleaning real-world customer data
* handling categorical and numerical preprocessing
* applying feature encoding and scaling
* training multiple machine learning classification models
* comparing models using standard evaluation metrics
* understanding how machine learning can be applied to churn prediction problems

---

## Repository Contents

* **Notebook / Python file** containing:

  * data cleaning
  * EDA
  * preprocessing
  * model training
  * evaluation

---

## Conclusion

This project demonstrates an end-to-end customer churn analysis workflow using Python and machine learning. By combining data preprocessing, visual analysis, and classification models, the project provides a practical understanding of how churn prediction can be approached in a telecom/business setting.

It also helped strengthen my understanding of **EDA, feature preprocessing, classification algorithms, and model evaluation** in a real-world business problem.
