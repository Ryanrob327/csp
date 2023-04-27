---
toc: true
layout: post
description: Data Analysis
categories: [week31]
title: Data Analysis Hacks
---

# Data/Predictive analysis

1. Numpy and pandas can be used for data cleaning, data transformation, data integration, feature selection, and data visualization
2. Linear regression, decision trees, random forests, neural networks, support vector machines
3. Business, healthcare, and education can all use data analysis to work more efficiently
4. Feature engineering is the process of selecting, transforming, and creating features from raw data to improve the performance of predictive models.
5. Deploying machine learning models for real-time predictive analysis involves several steps, including model training, evaluation, deployment, integration, and monitoring. First, the model is trained using historical data, and its performance is evaluated to ensure accuracy.
6. While NumPy and Pandas are powerful tools for data analysis, they do have some limitations. For example, NumPy is limited in its ability to handle missing or heterogeneous data, and Pandas can be slow for large datasets. In such cases, other data analysis tools such as Apache Spark, Dask, or Hadoop may be necessary. 
7. Predictive analysis can be used to improve decision-making and optimize business processes by identifying patterns and trends in data that can be used to make informed decisions. For example, predictive analysis can be used to forecast sales or customer behavior, identify areas for process improvement, or optimize supply chain management.
8. Example code:
   
```
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import accuracy_score

# Load data
df = pd.read_csv('customer_data.csv')

# Preprocess data
df = df.dropna()
X = df.drop(['customer_id', 'churned'], axis=1)
y = df['churned']
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Train model
clf = DecisionTreeClassifier()
clf.fit(X_train, y_train)

# Predict outcomes
y_pred = clf.predict(X_test)
accuracy = accuracy_score(y_test, y_pred)
print('Accuracy:', accuracy)

# Make predictions
new_customer = pd.DataFrame({'age': [35], 'gender': ['Male'], 'income': [50000], 'subscription_length': [6]})
prediction = clf.predict(new_customer)
print('Prediction:', prediction)
```

# Pandas



# Numpy

