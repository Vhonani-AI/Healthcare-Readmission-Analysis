# Health Readmission Prediction: Growing into Data

This project focuses on predicting the likelihood of hospital readmission within 30 days of discharge. By analyzing historical patient data, this work demonstrates how machine learning can be used to identify high-risk patients, potentially improving patient outcomes and optimizing healthcare resources.

## Project Overview

The goal of this project is to predict whether a patient will be readmitted to the hospital within 30 days of discharge. Using a dataset of 3,000 patient records, I explored how health markers, admission history, and hospital stay duration can be used to identify high-risk individuals. This project demonstrates the practical application of data processing, visualization, and predictive modeling in a healthcare context.

## The Dataset

The analysis is based on a dataset of 3,000 patient records, including:

- Demographics: Age and Gender.

- Admission Details: Admission type (Elective/Emergency) and Length of Stay.

- Health Markers: Blood Pressure, Blood Sugar Levels, and Number of Diagnoses.

- History: Number of previous admissions.

- Target: Readmission status (Yes/No).


**Methodology**

The project follows a structured data science workflow:

1. Data Preprocessing: Handling categorical encoding (Label Encoding) and feature scaling (StandardScaler) to ensure data is ready for modeling.

2. Exploratory Data Analysis (EDA): Visualizing distributions and correlations to understand the key drivers of readmission.

3. Model Implementation: Training and comparing four different algorithms:

- Decision Tree

- Random Forest

- K-Nearest Neighbors (KNN)

- XGBoost


4. Evaluation: Using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC to assess performance, with a focus on the challenges of class imbalance.



## Repository Structure

To keep the project organized and professional, I have structured the files as follows:

- /Raw Data: Contains the raw dataset (Expanded_Patient_Readmission_Dataset.csv) and the project requirement specifications (Expanded_Patient_Readmission.pdf).

- /Notebooks: Includes all Jupyter notebooks used for analysis, including versions optimized for Google Colab and Databricks.

- /Data Visualisations: Stores charts and plots generated during the analysis, such as the model performance comparison.

Tech Stack & Tools

- Language: Python

- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

- Platforms: Databricks, Google Colab


## Machine Learning Journey

In this project, I implemented and compared four different machine learning algorithms to understand their strengths and weaknesses:

| Metric | Best Performing Model (XGBoost) |
| --- | --- |
| **Accuracy** | 0.6817 |
| **ROC-AUC** | 0.5598 |
| **Recall** | 0.1988 |

## Key Insights:

- Feature Significance: Blood sugar levels, blood pressure, and length of stay emerged as the most critical predictors for readmission risk.

- Model Performance: While Random Forest had higher accuracy, XGBoost proved to be more effective at distinguishing between patient classes (higher ROC-AUC).

- The Challenge of Imbalance: This project taught me about the "Recall" challenge in imbalanced datasets—where a model might be accurate overall but struggle to find the specific "Yes" cases (readmissions).



I am continuously learning and expanding my skills. This project is a reflection of my curiosity and growth in the world of data.

