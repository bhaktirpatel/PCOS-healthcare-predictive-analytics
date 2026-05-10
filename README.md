# PCOS Disease Prediction using Machine Learning

This project focuses on predicting the risk of Polycystic Ovary Syndrome (PCOS) using healthcare and clinical data. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, and machine learning-based prediction.

The project was developed as part of a data analytics internship to understand how machine learning can support disease detection using medical datasets.

# Project Objective

The main objective of this project is to:

- Analyze PCOS-related healthcare parameters
- Identify important clinical and lifestyle-related risk factors
- Build machine learning models for disease prediction
- Compare model performance using evaluation metrics
- Understand the workflow of healthcare predictive analytics
- 
# Machine Learning Problem Type

- Learning Type: Supervised Machine Learning
- Problem Type: Binary Classification
- Target Variable: PCOS Status (PCOS / No PCOS)

The model predicts whether a patient is likely to have PCOS based on healthcare, hormonal, and lifestyle-related features.

# Dataset Information

The dataset contains healthcare records related to:

- Hormonal levels
- Menstrual cycle information
- BMI and body measurements
- Lifestyle-related factors
- Reproductive health indicators

The dataset was used only for educational and research purposes.

# Dataset Source

Kaggle PCOS Dataset:

https://www.kaggle.com/datasets/shreyasvedpathak/pcos-dataset

# Project Workflow

## 1. Data Cleaning and Preprocessing

The dataset was cleaned and standardized before analysis.

Steps performed:

- Renamed columns for readability
- Checked missing values
- Fixed inconsistent data types
- Removed duplicate records
- Prepared cleaned datasets for analysis
  
## 2. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and relationships within the dataset.

Visualizations included:

- PCOS distribution
- BMI distribution
- Waist-Hip Ratio analysis
- AMH level comparison
- Weight gain analysis
- Correlation heatmap

These visualizations helped identify trends associated with PCOS.

# Machine Learning Models Used

## Logistic Regression

Logistic Regression was used as a baseline classification model for predicting PCOS status.

## Random Forest Classifier

Random Forest was used to improve prediction performance and analyze feature importance.

# Feature Importance Analysis

Feature importance analysis was performed using the Random Forest model to identify the most influential healthcare parameters contributing to PCOS prediction.

# Model Evaluation

The models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- 
### Model Performance

- Logistic Regression Accuracy: ~88%
- Random Forest Accuracy: ~84%

The Logistic Regression model showed slightly better overall performance on this dataset.

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
  
# Project Structure
PCOS-healthcare-predictive-analytics
## Raw_Data
  Original healthcare dataset
## Processed
  Cleaned datasets
## Notebooks
  01_data_cleaning.ipynb
  02_eda_visualization.ipynb
  03_model_building.ipynb
  
# Ethical Considerations

This project uses anonymized healthcare data for educational purposes only.

No personally identifiable patient information was used. Ethical handling of healthcare data and patient privacy were considered throughout the project workflow.

# Conclusion

This project demonstrates how machine learning can be applied to healthcare datasets for disease prediction and risk analysis. It also highlights the importance of preprocessing, visualization, and model evaluation in building reliable predictive analytics workflows.
