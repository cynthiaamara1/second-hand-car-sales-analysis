# Second-Hand Car Sales Analysis using Machine Learning

## Project Overview

This project explores the application of **supervised** and **unsupervised machine learning** techniques to analyse and predict second-hand car prices in the United Kingdom.

Using a synthetic dataset of **50,000 used vehicles**, multiple machine learning models were developed, trained, evaluated and compared to identify the most accurate approach for predicting vehicle prices. Clustering algorithms were also applied to uncover hidden patterns within the dataset.

---

## Objectives

- Explore the dataset through Exploratory Data Analysis (EDA)
- Predict second-hand car prices using regression models
- Compare the performance of different machine learning algorithms
- Identify hidden customer and vehicle segments using clustering techniques
- Evaluate model performance using appropriate metrics

---

## Dataset

The dataset contains **50,000 synthetic UK used car records** with both numerical and categorical features.

### Numerical Features

- Mileage
- Engine Size
- Year of Manufacture
- Price

### Categorical Features

- Manufacturer
- Model
- Fuel Type

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

# Exploratory Data Analysis

The dataset was analysed to:

- Understand feature distributions
- Detect correlations
- Explore relationships between variables
- Prepare the data for machine learning

Key preprocessing steps included:

- One-Hot Encoding
- Label Encoding
- Feature Scaling
- Standardisation

---

# Machine Learning Models

## Supervised Learning

- Simple Linear Regression
- Polynomial Regression
- Multiple Linear Regression
- Random Forest Regressor
- Artificial Neural Network (ANN)

## Unsupervised Learning

- K-Means Clustering
- DBSCAN

---

# Model Performance

| Model | R² Score |
|---------|---------:|
| Linear Regression | 0.5111 |
| Polynomial Regression | 0.6094 |
| Multiple Linear Regression | 0.6715 |
| Random Forest | 0.9985 |
| Artificial Neural Network | **0.9992** |

### Best Performing Model

**Artificial Neural Network (ANN)**

Performance:

- R² Score: **0.9992**
- MAE: **315.44**
- RMSE: **473.15**

---

# Repository Structure

```
second-hand-car-sales-analysis/
│
├── README.md
├── requirements.txt
├── LICENSE
├── Second Hand Car Sales Analysis.ipynb
├── Second Hand Car Sales Analysis Report.pdf
├── data/
└── images/
```

---

# Future Improvements

Possible extensions include:

- XGBoost Regressor
- LightGBM
- Feature Importance Analysis

---

# 📄 Files Included

- Jupyter Notebook
- Technical Report
- Requirements File

---

## Author

**Cynthia Amarachi Eze**
---

If you found this project interesting, feel free to star the repository.
