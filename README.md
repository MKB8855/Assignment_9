# Assignment_9

## Project Overview
This project aims to predict whether a borrower will pay back their loan in full based on several financial and personal attributes. We utilize the LendingClub dataset and compare two machine learning models: a single **Decision Tree** and a **Random Forest Classifier**.

## Key Features
- **Exploratory Data Analysis (EDA):** Visualized FICO scores, interest rates, and loan purposes using Seaborn and Matplotlib.
- **Data Preprocessing:** Handled categorical variables using one-hot encoding (dummies).
- **Modeling:** Implemented a Random Forest with 600 estimators to improve prediction accuracy.
- **Evaluation:** Analyzed performance using Classification Reports and Confusion Matrices.

## Results
The Random Forest model outperformed the Decision Tree, achieving an overall accuracy of approximately 85%. However, both models highlighted challenges in predicting the minority class ("not fully paid") due to the imbalanced nature of the dataset.
