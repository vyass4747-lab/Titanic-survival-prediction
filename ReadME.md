# Titanic Survival Prediction using Classification Algorithms

## Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning classification algorithms. The objective is to compare the performance of multiple classification models on the Titanic dataset and identify the most effective approach for survival prediction.

The project includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and comparison of different classification algorithms.

---

## Dataset

The dataset used is the Titanic dataset available through Seaborn/Kaggle.

### Features Used

* Passenger Class (Pclass)
* Sex
* Age
* SibSp (Number of siblings/spouses aboard)
* Parch (Number of parents/children aboard)
* Fare
* Embarked

### Target Variable

* Survived

  * 1 = Survived
  * 0 = Did Not Survive

---

## Data Preprocessing

The following preprocessing steps were performed:

* Handling missing values
* Removing unnecessary and highly redundant columns
* Encoding categorical variables
* Feature selection
* Train-Test Split
* Feature Scaling (for algorithms that require scaling)

---

## Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Survival distribution
* Gender-wise survival rate
* Passenger class impact on survival
* Age distribution
* Fare distribution
* Correlation between features

Visualization libraries used:

* Matplotlib
* Seaborn

---

## Machine Learning Algorithms Implemented

The following classification algorithms were trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Naive Bayes
5. Support Vector Machine (SVM)


---

## Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision
* Recall
* Confusion Matrix
* Cross Validation

The performance of all algorithms was compared to identify the best-performing model.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Train-Test Split
       ↓
Feature Scaling
       ↓
Model Training
       ↓
Cross Validation
       ↓
Model Evaluation
       ↓
Performance Comparison
```

## Results

The project demonstrates how different classification algorithms perform on the same dataset and highlights the importance of preprocessing, feature engineering, and proper model evaluation in machine learning workflows.
And according to me in the Titanic Dataset that are available on seaborn has more accuracy  with SVC(support vector machine) algorithm with 0.827 crosss validation mean

---

## Learning Outcomes

Through this project, I gained hands-on experience with:

* Data preprocessing techniques
* Feature engineering
* Classification algorithms
* Model evaluation metrics
* Cross Validation
* Hyperparameter understanding
* End-to-end Machine Learning workflow

---

## Future Improvements

* Hyperparameter tuning using GridSearchCV
* Ensemble techniques
* Feature importance analysis
* Deployment using Flask/Django
* Interactive prediction interface

---

## Author

Suhani Vyas

Aspiring AI & Machine Learning Engineer passionate about Machine Learning, Generative AI, RAG Systems, and Agentic AI applications.
