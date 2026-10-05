# Intro to AI – Machine Learning Project

This project explores several fundamental machine learning and deep learning techniques through regression and image classification tasks.

The project includes data exploration, preprocessing, model comparison, hyperparameter tuning, and evaluation using both classical machine learning models and neural networks.

## Project Overview

The project is divided into three main parts:

### 1. Fuel Efficiency Prediction – Regression

The **Auto MPG dataset** from the UCI Machine Learning Repository is used to predict vehicle fuel efficiency (`mpg`) based on features such as:

- Cylinders
- Displacement
- Horsepower
- Weight
- Acceleration
- Model year
- Origin

The workflow includes:

- Exploratory Data Analysis (EDA)
- Missing-value handling using median imputation
- Feature standardization
- Linear Regression
- Polynomial Regression
- K-Nearest Neighbors (KNN) Regression
- Comparison of batch and mini-batch gradient descent
- Bias–variance and model complexity analysis

The Linear Regression baseline achieved an **R² score of approximately 0.85**.

Polynomial Regression and KNN were also evaluated in order to examine nonlinear relationships and the effect of model complexity.

---

### 2. Classical Image Classification – CIFAR-10

The second part of the project focuses on image classification using the **CIFAR-10 dataset**.

Three classical machine learning models were compared:

- Logistic Regression
- Linear SVM
- K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed for the regularization parameter `C` and the number of neighbors `k`.

Among the baseline models, **Logistic Regression achieved the highest validation accuracy of 29%**.

Confusion matrices were also used to analyze classification performance across the CIFAR-10 classes.

---

### 3. Neural Network Classification with PyTorch

The final part implements a **Convolutional Neural Network (CNN)** using PyTorch for CIFAR-10 image classification.

The architecture includes:

- Multiple convolutional layers
- ReLU activation
- Batch normalization
- Max pooling
- Dropout regularization
- Fully connected layers

The model was trained using the **Adam optimizer**, with additional hyperparameter experiments for different learning rates.

The final CNN achieved approximately **84–85% validation accuracy within 10 epochs**, significantly improving over the classical machine learning approaches.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- PyTorch
- Torchvision
- UCI Machine Learning Repository
- Google Colab

## Key Concepts

This project demonstrates:

- Exploratory Data Analysis
- Data preprocessing and normalization
- Regression
- Classification
- Model evaluation
- Hyperparameter tuning
- Bias–variance tradeoff
- Overfitting and regularization
- Gradient descent
- Convolutional Neural Networks
- Deep learning with PyTorch

## Files

`Intro_to_AI_SAPIR_HAI.ipynb` – complete implementation, experiments, visualizations, and model evaluation.
