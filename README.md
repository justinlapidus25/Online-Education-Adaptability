<img src="https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/bc5dad8c-06ed-405c-8f6e-fecfd5ccaa15" alt="Banner Image" width="200%">

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
![download](https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/24725692-f883-46ea-870d-fcf8d105db86)



## Model Evaluation Summary:

### Logistic Regression Pipeline:
#### Accuracy: 71.37%

### Random Forest Classifier Pipeline:
#### Accuracy: 89.21%
#### Best Hyperparameters: {'n_estimators': 200, 'max_depth': None, 'min_samples_split': 2, 'min_samples_leaf': 1}

## Best Peforming Model

### XGB Classifier Pipeline:
#### Accuracy: 91.29%
#### Best Hyperparameters: {'learning_rate': 0.2, 'max_depth': 7, 'min_child_weight': 3, 'n_estimators': 200}

![download-1](https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/e33c5aa2-690e-4027-817c-b15efaf8f4c1)

### SVM Pipeline:
#### Accuracy: 86.72%
#### Best Hyperparameters: {'C': 1, 'kernel': 'rbf', 'gamma': 'scale'}

### Decision Tree Classifier Pipeline:
#### Accuracy: 90.87%
#### Best Hyperparameters: {'max_depth': 15, 'min_samples_leaf': 1, 'min_samples_split': 2}

## Worst Performing Model

### Gaussian Naive Bayes Pipeline:
#### Accuracy: 62.24%

![download-2](https://github.com/justinlapidus25/Online-Education-Adaptability/assets/130884190/bc0330e6-85ca-4fc1-b443-a91b35989274)
## Overall Conclusion:

## Among the models tested, the XGB Classifier pipeline achieved the highest accuracy at 91.29%, closely followed by the Random Forest Classifier with an accuracy of 89.21%. The choice of the best model depends on various factors, including the specific requirements of the problem, interpretability, and computational resources. It's essential to consider other metrics, such as precision, recall, and F1-score, to get a more comprehensive understanding of the model's performance, especially in imbalanced datasets. 
