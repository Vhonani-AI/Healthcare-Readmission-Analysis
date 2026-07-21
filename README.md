# Health Readmission Prediction: Growing into Data

This repository contains my standalone project on predicting hospital readmission risk. It marks a significant milestone in my journey of growing into data, where I've moved from basic Python exercises to building a complete, end-to-end machine learning pipeline.

## Project Overview

The goal of this project is to predict whether a patient will be readmitted to the hospital within 30 days of discharge. Using a dataset of 3,000 patient records, I explored how health markers, admission history, and hospital stay duration can be used to identify high-risk individuals. This project demonstrates the practical application of data processing, visualization, and predictive modeling in a healthcare context.

## Repository Structure

To keep the project organized and professional, I have structured the files as follows:

- /data: Contains the raw dataset (Expanded_Patient_Readmission_Dataset.csv) and the project requirement specifications (Expanded_Patient_Readmission.pdf).

- /notebooks: Includes all Jupyter notebooks used for analysis, including versions optimized for Google Colab and Databricks.

- /visualizations: Stores charts and plots generated during the analysis, such as the model performance comparison.

Tech Stack & Tools

- Language: Python

- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

- Platforms: Databricks, Google Colab


## Machine Learning Journey

In this project, I implemented and compared four different machine learning algorithms to understand their strengths and weaknesses.

## Key Insights:

- Feature Significance: Blood sugar levels, blood pressure, and length of stay emerged as the most critical predictors for readmission risk.

- Model Performance: While Random Forest had higher accuracy, XGBoost proved to be more effective at distinguishing between patient classes (higher ROC-AUC).

- The Challenge of Imbalance: This project taught me about the "Recall" challenge in imbalanced datasets—where a model might be accurate overall but struggle to find the specific "Yes" cases (readmissions).



I am continuously learning and expanding my skills. This project is a reflection of my curiosity and growth in the world of data.

