# Driving Style Classification Project

## Introduction
This project aims to classify driving styles using a variety of machine learning models and a neural network. The dataset comprises vehicle and environmental attributes, and the project involves multiple stages of data preparation, exploration, feature engineering, modeling, and evaluation. The project follows an agile/SCRUM methodology with clearly defined sprints, objectives, tasks, and reviews.

## Table of Contents
1. [Sprint 1: Data Preparation](#sprint-1-data-preparation)
2. [Sprint 2: Exploratory Data Analysis](#sprint-2-exploratory-data-analysis)
3. [Sprint 3: Feature Engineering and Safety Analysis](#sprint-3-feature-engineering-and-safety-analysis)
4. [Sprint 4: Preprocessing and Dimensionality Reduction](#sprint-4-preprocessing-and-dimensionality-reduction)
5. [Sprint 5: Model Implementation and Evaluation](#sprint-5-model-implementation-and-evaluation)

## Sprint 1: Data Preparation

### Objective
Ensure the dataset is clean and ready for analysis and modeling.

### Key Activities
- Merged multiple datasets using a common key.
- Handled missing data by removing variables with high missing rates and planning imputation for others.
- Identified and removed duplicate records.

### Outcome
A consolidated and clean dataset ready for exploratory analysis.

## Sprint 2: Exploratory Data Analysis

### Objective
Understand the relationships between variables and identify key patterns.

### Key Activities
- Conducted Chi-Square tests to explore relationships between categorical variables.
- Performed correlation analysis to identify clusters of highly correlated features.
- Visualized data distributions and identified potential outliers.

### Outcome
Insights into variable relationships and initial identification of important features.

## Sprint 3: Feature Engineering and Safety Analysis

### Objective
Create new features to enhance the dataset and assess potential safety risks.

### Key Activities
- Discretized continuous variables into meaningful categories.
- Calculated new features such as momentum and kinetic energy.
- Evaluated braking distances and physical distances between vehicles to assess collision risks.

### Outcome
An enriched dataset with new features that provide deeper insights into vehicle dynamics and safety.

## Sprint 4: Preprocessing and Dimensionality Reduction

### Objective
Prepare the dataset for modeling by handling missing values, transforming data, and reducing dimensionality.

### Key Activities
- Imputed missing values and visualized key variable distributions.
- Transformed and standardized numerical features.
- Applied Principal Component Analysis (PCA) to reduce the number of features while retaining essential information.

### Outcome
A preprocessed dataset with reduced dimensionality, ready for machine learning model training.

## Sprint 5: Model Implementation and Evaluation

### Objective
Train and evaluate various machine learning models to classify driving styles.

### Key Activities
- Implemented and compared multiple models including Logistic Regression, Random Forest, XGBoost, and a Feedforward Neural Network.
- Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.
- Visualized model performance and documented findings.

### Outcome
A comprehensive evaluation of multiple models with detailed performance metrics, leading to insights on the most effective approach for driving style classification.

## Conclusion
This project successfully implemented a structured approach to classify driving styles using machine learning techniques. Each sprint focused on key aspects of the data science workflow, from data preparation and exploration to feature engineering, preprocessing, and model evaluation. Future work will focus on hyperparameter tuning, feature engineering, and planning for model deployment and integration.

---