Author
Harsheen Kaur

LinkedIn:
https://www.linkedin.com/in/harsheen285/

GitHub:
https://github.com/Harsheen-Kaur-Projects

# SmartPriceAI - Smartphone Price Category Prediction using Machine Learning

An end-to-end Machine Learning classification project that predicts the price category of smartphones based on their technical specifications.

The model classifies smartphones into three categories:

- Budget
- Mid-range
- Premium

The project demonstrates a complete Machine Learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter optimization, evaluation, and prediction.

---

# Problem Statement

Smartphone pricing depends on multiple hardware and software specifications such as RAM, storage, battery capacity, camera features, processor performance, display specifications, and connectivity features.

The objective of this project is to build a Machine Learning model that can automatically classify smartphones into different price segments using their specifications.

---

# Project Objectives

- Clean and preprocess smartphone specification data
- Perform exploratory data analysis
- Analyze relationships between smartphone features and pricing
- Engineer meaningful performance-based features
- Train multiple classification algorithms
- Compare model performance
- Optimize the best-performing model
- Evaluate predictions using classification metrics

---

# Dataset

The dataset contains smartphone specifications including:

- Smartphone model
- Rating
- RAM
- Internal storage
- Battery capacity
- Fast charging capability
- Processor clock speed
- Camera specifications
- Display specifications
- Operating system
- Network capabilities
- Connectivity features

Target Variable:

```
price_category
```

Categories:

```
Budget
Mid-range
Premium
```

---

# Technologies Used

## Programming Language

- Python

## Data Analysis

- Pandas
- NumPy

## Data Visualization

- Matplotlib
- Seaborn

## Machine Learning

- Scikit-learn

Algorithms implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Optimization:

- RandomizedSearchCV

---

# Project Workflow


Data Collection

↓

Data Cleaning & Preprocessing

↓

Exploratory Data Analysis

↓

Feature Engineering

↓

Feature Encoding

↓

Train-Test Split

↓

Model Training

↓

Hyperparameter Optimization

↓

Model Evaluation

↓

Final Price Category Prediction


---

# Feature Engineering

Additional features were created to improve model understanding:

- Storage to RAM ratio
- Battery efficiency score
- Charging power ratio
- Performance score
- Camera score
- Pixel density
- Battery-storage relationship
- RAM-clock performance score
- Camera sensor efficiency


---

# Exploratory Data Analysis

The project includes visual analysis such as:

- Smartphone distribution by price category
- Important features affecting price classification
- Model accuracy comparison
- Feature importance ranking
- Confusion matrix visualization
- Final model performance metrics


---

# Machine Learning Models

The following classification models were trained:

## 1. Logistic Regression

Used as a baseline classification model.

## 2. Decision Tree Classifier

Used to capture non-linear relationships between smartphone specifications.

## 3. Random Forest Classifier

Used as the primary ensemble learning approach.

Hyperparameter optimization was performed using:

```
RandomizedSearchCV
```

---

# Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix


---

# Key Features

✔ Complete Machine Learning pipeline

✔ Data preprocessing

✔ Feature engineering

✔ Exploratory data analysis

✔ Multiple classification models

✔ Hyperparameter tuning

✔ Model comparison

✔ Prediction on new smartphone specifications

✔ Data visualization for insights


---

# Future Improvements

Possible enhancements:

- Deploy model using Streamlit
- Create interactive smartphone price prediction dashboard
- Add larger smartphone datasets
- Implement XGBoost / LightGBM / CatBoost
- Add automated model monitoring
- Build REST API using Flask or FastAPI


---

# Skills Demonstrated

- Python Programming
- Data Cleaning
- Data Analysis
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning Classification
- Model Evaluation
- Data Visualization
- Business Analytics


---
# License

This project is licensed under the MIT License.
