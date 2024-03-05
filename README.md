# Heart-Disease-Classification
This project aims to predict the presence of heart disease based on various medical attributes. The dataset used in this project is "heart-disease.csv".

# Overview
The project involves the following steps:
1) Exploratory Data Analysis (EDA)
2) Preprocessing of Data
3) Building and Tuning Machine Learning Models
4) Evaluation of Model Performance
   
# Libraries Used
-Pandas<br />
-NumPy<br />
-Matplotlib<br />
-Seaborn<br />
-Scikit-Learn

# File Description
-heart-disease.csv: Dataset containing medical attributes and the target variable indicating the presence of heart disease.<br />
-heart_disease_classification.ipynb: Jupyter notebook containing the code for data analysis, model building, and evaluation.

# Exploratory Data Analysis (EDA)
-Visualized the dataset to understand the distribution of variables and their relationships.<br />
-Investigated missing values and checked the data types.<br />
-Analyzed the correlation among features using a heatmap and scatter plots.

# Model Building
-Utilized logistic regression, K-nearest neighbors, and random forest classifiers.<br />
-Employed cross-validation to evaluate model performance.<br />
-Tuned hyperparameters using RandomizedSearchCV and GridSearchCV.

# Model Evaluation
-Evaluated models based on accuracy, precision, recall, and F1-score.<br />
-Visualized results using bar plots and ROC curves.<br />
-Explored feature importance using logistic regression coefficients.

# Reduced Feature Set
-Created a reduced feature set by removing less significant features.<br />
-Re-evaluated the logistic regression model with the reduced feature set.<br />
-Compared the performance metrics of the models with all features and the reduced feature set.

# Conclusion
-The project demonstrates the process of predicting heart disease using machine learning techniques.<br />
-Tuning hyperparameters and feature selection significantly impact model performance.<br />
-The final model achieves [insert performance metrics] accuracy on test data.
