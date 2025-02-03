# Diabetes Readmission Prediction using PySpark

## Project Overview
This project is part of two graduate-level courses: [**Big Data Analytics and Text Mining**](https://www.unibo.it/en/study/phd-professional-masters-specialisation-schools-and-other-programmes/course-unit-catalogue/course-unit/2024/491926), and [**Project Work in Big Data Analytics and Text Mining**](https://www.unibo.it/en/study/phd-professional-masters-specialisation-schools-and-other-programmes/course-unit-catalogue?codiceMateria=B3157&annoAccademico=2024&codiceCorso=9063&single=True&search=True). The project is supervised by **Professor Stefano Lodi** and focuses on predictive modeling using the **Diabetes 130-US Hospitals Dataset** from the **UCI Machine Learning Repository**.

## Dataset Information
- **Dataset Name**: [Diabetes 130-US Hospitals Dataset](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008)
- **Source**: UCI Machine Learning Repository
- **Size**:
  - **N ≥ 100,000** patterns
  - **p = 47** features
  - **Total Data Points (N×p) ≥ 4,700,000**

## Tools and Technologies
- **Big Data Framework**: Apache **PySpark**
- **Machine Learning Algorithms Used**:
  - Logistic Regression
  - Random Forest
  - Gradient Boosted Trees (GBT)
  - Decision Trees
  - Linear Support Vector Classifier (SVC)
  - Naive Bayes

## Analysis Plan

### 1. Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Utilizing Spark DataFrames for summary statistics.
- **Visualization**: Graphical representation of key features.
- **Correlation Analysis**: Examining relationships between features and the target variable (readmission).

### 2. Data Preprocessing
- **Handling Missing Values**: Using Spark’s built-in functions for data imputation.
- **Feature Engineering**:
  - Encoding categorical variables using **VectorAssembler** and **OneHotEncoder**.
  - Scaling and normalization with **StandardScaler**.

### 3. Model Development
- **Dataset Splitting**: Train-test split using **PySpark**.
- **Model Training & Hyperparameter Tuning**:
  - Implementing PySpark’s **ML Pipeline**.
  - Using **Cross-validation** to improve generalization and prevent overfitting.

### 4. Model Evaluation
- **Performance Metrics**:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **AUC-ROC**
- **Comparison of Models**:
  - Evaluating models based on predictive performance and computational efficiency.

### 5. Discussion
- **Results Interpretation**: Understanding model predictions and their significance.
- **Key Insights**:
  - Identifying significant features influencing **diabetes patient readmissions**.
  - Assessing the role of different machine learning models in medical data prediction.

## How to Run the Project
### Prerequisites
- Install **Apache Spark** and **PySpark**.
- Ensure dependencies like **matplotlib**, **pandas**, and **scikit-learn** are installed.

### Execution Steps
1. Load the dataset from the **UCI Machine Learning Repository**.
2. Perform **EDA** and data preprocessing.
3. Train multiple models using **PySpark’s ML library**.
4. Evaluate models and compare results.
5. Interpret the findings and draw conclusions.

## Author
Taleb Zarhesh

taleb.zarhesh@gmail.com

taleb.zarhesh@studio.unibo.it

---

**Note**: This project aims to leverage **Big Data Analytics and Machine Learning** techniques to enhance the understanding of diabetes readmissions, providing insights into patient management and hospital readmission factors.

