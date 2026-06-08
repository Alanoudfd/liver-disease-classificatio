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

![Correlation Heatmap](images/correlation_heatmap.png)

### Outlier Detection using KNN and LOF

![Outlier Analysis](images/outlier_analysis.png)

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

![Model Comparison](images/model_comparison.png)

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

