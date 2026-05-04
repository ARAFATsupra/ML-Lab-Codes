# Machine Learning Lab — Google Colab Notebooks

**Student:** Kazi Arafat Hossain  

---

## Overview

This repository contains all Machine Learning Lab notebooks, datasets, and practice files completed during the course. Each notebook is written in Python and designed to run on **Google Colab**. The experiments cover core supervised learning topics including linear regression, multiple regression, regularization, classification, and model evaluation using real-world datasets.

---

## Repository Structure

```
ML-Lab-Codes/
|
|-- notebooks/
|   |-- ML Lab Task 1.ipynb
|   |-- ML Lab Task 2.ipynb
|   |-- ML Lab Task 3.ipynb
|   |-- ML Lab Task 4.ipynb
|   |-- Machine Learning Lab Evaluation.ipynb
|   |-- Practice.ipynb
|   |-- Regularization.ipynb
|   |-- Iris Dataset
|   |-- MNISt Dataset
|
|-- datasets/
|   |-- housing.csv
|   |-- iris.csv
|   |-- tested.csv
|   |-- mnist/
|       |-- t10k-images-idx3-ubyte
|       |-- t10k-labels-idx1-ubyte
|       |-- train-images-idx3-ubyte
|       |-- train-labels-idx1-ubyte
|
|-- README.md
```

---

## Notebooks

### ML Lab Task 1 — Simple Linear Regression

**File:** `notebooks/ML Lab Task 1.ipynb`

Implements simple linear regression to predict **median house price** using **median income** as the sole predictor. The notebook covers data loading from Google Drive, exploratory data analysis, correlation analysis, model training using Scikit-learn, and evaluation using Mean Squared Error (MSE) and R-squared score. A scatter plot with the regression line is included.

**Dataset used:** `housing.csv`  
**Key concepts:** Simple linear regression, correlation coefficient, MSE, R2 score

---

### ML Lab Task 2 — Multiple Linear Regression

**File:** `notebooks/ML Lab Task 2.ipynb`

Extends the regression model to use multiple input features for predicting house prices. The notebook demonstrates feature selection, handling of non-numeric columns, data preprocessing, and comparison of model performance when multiple predictors are included versus a single predictor.

**Dataset used:** `housing.csv`  
**Key concepts:** Multiple linear regression, feature engineering, multicollinearity

---

### ML Lab Task 3 — Regression Analysis and Correlation Study

**File:** `notebooks/ML Lab Task 3.ipynb`

A comprehensive regression task that includes correlation matrix computation, feature importance ranking, data visualization using heatmaps and scatter plots, and regression model training. The notebook explores which features have the strongest relationship with the target variable and builds a regression pipeline accordingly.

**Dataset used:** `housing.csv`  
**Key concepts:** Correlation matrix, feature importance, data visualization, regression pipeline

---

### ML Lab Task 4 — Classification with MNIST

**File:** `notebooks/ML Lab Task 4.ipynb`

Implements an image classification model using the MNIST handwritten digits dataset. The notebook loads the dataset using TensorFlow/Keras, builds a neural network classifier, trains the model, and evaluates accuracy on the test set. Prediction outputs and sample images are displayed.

**Dataset used:** MNIST (`mnist/` folder)  
**Key concepts:** Classification, neural networks, TensorFlow, Keras, image data

---

### Machine Learning Lab Evaluation

**File:** `notebooks/Machine Learning Lab Evaluation.ipynb`

**Student:** Kazi Arafat Hossain | **ID:** 232-51-008 | **Set:** A

The formal lab evaluation notebook. Uses the Titanic dataset to perform data exploration, preprocessing, model training, and performance evaluation. Tasks include handling missing values, encoding categorical features, training a classifier, and reporting accuracy metrics.

**Dataset used:** `tested.csv` (Titanic dataset)  
**Key concepts:** Classification, data preprocessing, missing value handling, model evaluation

---

### Practice

**File:** `notebooks/Practice.ipynb`

A practice notebook exploring regression and correlation analysis techniques. Covers computing correlation matrices, identifying significant features, and building regression models. Also includes experiments with career guidance data.

**Key concepts:** Correlation analysis, exploratory data analysis, regression experimentation

---

### Regularization

**File:** `notebooks/Regularization.ipynb`

Demonstrates regularization techniques applied to linear regression. The notebook covers Ridge and Lasso regression, compares model performance with and without regularization, handles missing values, applies StandardScaler for feature normalization, and visualizes how regularization affects model coefficients and overfitting.

**Dataset used:** `housing.csv`  
**Key concepts:** Ridge regression, Lasso regression, L1/L2 regularization, StandardScaler, overfitting

---

## Datasets

| File | Description | Size |
|---|---|---|
| `housing.csv` | California housing dataset with features like median income, house age, ocean proximity, and median house value | ~1.4 MB |
| `iris.csv` | Classic Iris flower dataset with sepal/petal measurements for 3 species | ~4 KB |
| `tested.csv` | Titanic passenger dataset used for classification evaluation (survival prediction) | ~29 KB |
| `mnist/t10k-images-idx3-ubyte` | MNIST test set images (10,000 handwritten digit images) | ~7.5 MB |
| `mnist/t10k-labels-idx1-ubyte` | MNIST test set labels | ~10 KB |
| `mnist/train-images-idx3-ubyte` | MNIST training set images (60,000 handwritten digit images) | ~45 MB |
| `mnist/train-labels-idx1-ubyte` | MNIST training set labels | ~59 KB |

> **Note:** The file `train-images-idx3-ubyte` is 45 MB. GitHub does not allow uploading files larger than 25 MB through the web interface. To upload this file, you must use Git with Git LFS (Large File Storage), or skip it and load MNIST directly in the notebook using `tensorflow.keras.datasets.mnist.load_data()`, which is the recommended approach in lab notebooks.

---

## How to Run the Notebooks

**Step 1:** Open [Google Colab](https://colab.research.google.com)

**Step 2:** Click **File > Upload Notebook** and select any `.ipynb` file from this repository

**Step 3:** Upload the required dataset files to your Google Drive inside a folder named `Dataset`

**Step 4:** Run the cells from top to bottom using **Runtime > Run All**

---

## Libraries and Tools Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Google Colab

---

## Academic Integrity

All notebooks in this repository are original coursework submitted by the student listed above. The code is intended for educational reference only.
