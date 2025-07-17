# IRIS-Classification-Model
This project analyzes the Iris dataset using various machine learning techniques. It involves data preprocessing, dimensionality reduction with PCA, and classification using algorithms like KNN, SVM, and Decision Tree, Logistic Regression. The goal is to compare model performances and explore anomaly detection and rare models for improved insights.

<img width="435" height="508" alt="image" src="https://github.com/user-attachments/assets/ee960e93-6662-48f6-bc64-ec787b775c3c" />
<br>Applying PCA 

<img width="1389" height="590" alt="image" src="https://github.com/user-attachments/assets/bf611623-5893-4c68-8939-091477ced3a3" />
# Iris Dataset PCA Transformation

## Given Data

| sepal_length | sepal_width | petal_length | petal_width | species     |
|--------------|-------------|--------------|-------------|-------------|
| 5.1          | 3.5         | 1.4          | 0.2         | Iris-setosa |
| 4.9          | 3.0         | 1.4          | 0.2         | Iris-setosa |
| 4.7          | 3.2         | 1.3          | 0.2         | Iris-setosa |
| 4.6          | 3.1         | 1.5          | 0.2         | Iris-setosa |
| 5.0          | 3.6         | 1.4          | 0.2         | Iris-setosa |

## Transformed Data (After LabelEncoding/PCA)

| sepal_length | sepal_width | species | PCA_Combined |
|--------------|-------------|---------|--------------|
| 5.1          | 3.5         | 0       | -1.876838    |
| 4.9          | 3.0         | 0       | -1.876838    |
| 4.7          | 3.2         | 0       | -1.917048    |
| 4.6          | 3.1         | 0       | -1.836627    |
| 5.0          | 3.6         | 0       | -1.876838    |
