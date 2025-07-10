# Heart-Disease-Prediction

- This is Machine learning model for heart disease prediction
- This project aims to compare the performance of different classifications models using both the train test split and cross validation techniques.

# Dataset
- The Dataset is taken from kaggle:  https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
- The dataset contains a CSV file with ``1025 rows`` and ``14 colums`` with features such as ``age``, ``gender``, ``cp``, ``restecg``, etc.

# Libraries used:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn

# Preprocessing
- Checked for the missing values
- Standardize the data using ``StandardScaler``

# EDA and VISUALIZATION
- Use plys such as countplot. histplot and scatterplot to visualize the relationship between the features.
  
# Data Splitting
- Used both train test split and cross validation techniques.

# Modeling
- Models used are 
- ``Logistic Regression``
- ``KNN``
- ``Decision Tree``
- ``Random Forest``
- ``SVM``
- ``Naive Bayes``

# Evaluation
- Accuracy and f1 score

# Result
- Logistic Regression performed well compared to the other models
