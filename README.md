# Liver Disease Classification Using Machine Learning

## Project Overview

This project investigates the application of machine learning techniques for liver disease prediction using clinical patient data. The workflow included data preprocessing, exploratory data analysis, feature selection, outlier detection, model training, and hyperparameter optimization to identify the most effective classification model.

## Dataset

The project uses the Indian Liver Patient Dataset (ILPD), which contains demographic and clinical measurements collected from liver patients and healthy individuals. The objective is to classify whether a patient has liver disease based on laboratory test results and medical attributes.
### Dataset Source:
https://www.kaggle.com/datasets/uciml/indian-liver-patient-records

## Data Preprocessing

* Handled missing values using mean imputation
* Encoded categorical variables using one-hot encoding
* Performed correlation analysis for feature selection
* Conducted outlier analysis using K-Nearest Neighbors (KNN) and Local Outlier Factor (LOF)

## Exploratory Data Analysis

Statistical analysis and visualizations were used to better understand the dataset and identify important patterns.

### Correlation Heatmap

<img width="775" height="699" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/7b0dd01d-63ef-4c19-a0e6-ac62fc6c06a3" />


### Outlier Detection using KNN and LOF
<img width="469" height="216" alt="outlier_analysis" src="https://github.com/user-attachments/assets/9f8dfa4c-5b26-4725-9cb5-7c38e7a7a8b0" />


## Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

## Hyperparameter Tuning

GridSearchCV was applied to optimize model hyperparameters and improve predictive performance.

## Results

| Model                     | Accuracy |
| ------------------------- | -------- |
| Logistic Regression       | 57%      |
| Tuned Logistic Regression | 74%      |
| Decision Tree             | 68%      |
| Tuned Decision Tree       | 70%      |
| Random Forest             | 72%      |
| Tuned Random Forest       | 75%      |

### Model Comparison
<img width="474" height="283" alt="model_comparison" src="https://github.com/user-attachments/assets/4b871d2f-6fed-4fe9-8910-266a8f45efe4" />


## Key Findings

* Hyperparameter tuning improved the performance of all classification models.
* Random Forest consistently delivered the most balanced classification results.
* The Tuned Random Forest model achieved the highest overall performance with 75% accuracy.
* Feature selection and preprocessing significantly contributed to model effectiveness.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Skills Demonstrated

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Outlier Detection
* Machine Learning
* Hyperparameter Tuning
* Model Evaluation
* Data Visualization

