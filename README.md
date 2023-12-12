# Online-Education-Adaptability

Certainly! Below is a simplified version formatted as a README:

# Online Education Adaptability Prediction

## Overview

This project aims to predict students' adaptability levels in online education using various machine learning models. The dataset "students_adaptability_level_online_education.csv" is explored and preprocessed to develop and evaluate different pipelines.

## Importing Necessary Libraries

Libraries such as pandas, LabelEncoder, OneHotEncoder, seaborn, matplotlib.pyplot, and others are imported for data manipulation, preprocessing, visualization, and machine learning tasks.

## Data Loading and Initial Exploration

The dataset is loaded using `pd.read_csv`, and initial exploration includes methods like `isna().sum()` and `info()` to check for missing values, understand data types, and non-null counts.

## Handling Ordinal and Nominal Categories

Unique values for each column are displayed to understand categorical features. Categorical features are categorized into nominal and ordinal categories. One-hot encoding is performed on nominal categories using OneHotEncoder, and label encoding is applied to ordinal categories.

## Exploratory Data Analysis (EDA)

EDA involves exploring relationships between various categorical features and the target variable 'Adaptivity Level' using count plots. A correlation heatmap is also plotted to visualize the correlation between different features.
<img width="755" alt="Screen Shot 2023-12-12 at 12 30 17 PM" src="https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/45281838-9843-4dfd-a52b-4f4182cdc12a">
<img width="763" alt="Screen Shot 2023-12-12 at 12 30 11 PM" src="https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/43a2037a-863e-4122-82a2-4280736eaae1">
<img width="771" alt="Screen Shot 2023-12-12 at 12 30 06 PM" src="https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/e650ff59-f380-426d-8aa9-10487a568d5b">
<img width="753" alt="Screen Shot 2023-12-12 at 12 30 00 PM" src="https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/60bf6ceb-c021-4651-b50c-ae8e9dad8f90">
<img width="750" alt="Screen Shot 2023-12-12 at 12 29 49 PM" src="https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/f6e293fc-587f-4398-bd00-24f137c07331">

![download](https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/74ffc7ac-ffe6-4948-b414-53e8317d75d7)


## Model Pipelines and Accuracy Scores

### Logistic Regression Pipeline

- Accuracy: 71.37%

### Random Forest Classifier Pipeline

- Accuracy: 89.21%

### XGB Classifier Pipeline

- Accuracy: 91.29%
![download-1](https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/9ad536b3-a90b-4a4d-9776-01256d2da7a0)

### SVM Pipeline

- Accuracy: 86.72%

### Decision Tree Classifier Pipeline

- Accuracy: 90.87%

### Gaussian Naive Bayes Pipeline

- Accuracy: 62.24%
![download-2](https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/a8e73315-a614-48c4-b9d0-6be6fed7dfc0)


These accuracy scores represent the performance of each model in predicting students' adaptability levels in online education. The XGB Classifier pipeline achieved the highest accuracy among the models evaluated.
