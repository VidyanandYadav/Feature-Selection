# Feature Selection

A practical implementation and study of **Feature Selection techniques** using Python and Machine Learning.

This repository contains well-documented Jupyter Notebooks covering the three major approaches to feature selection:

- 🔹 Filter Methods
- 🔹 Wrapper Methods
- 🔹 Embedded Methods

Each notebook explains the concepts step-by-step and includes practical implementation, analysis, and results.

---

## 📌 What is Feature Selection?

Feature Selection is the process of selecting the most relevant features from a dataset while removing irrelevant or redundant features.

It helps to:

- Reduce the dimensionality of the dataset
- Improve model performance
- Reduce overfitting
- Decrease training time
- Improve model interpretability
- Remove irrelevant and redundant features

Instead of using every available feature, feature selection helps us identify the features that contribute the most to the prediction task.

---

## 🧠 Types of Feature Selection

There are three major approaches to feature selection:

### 1. Filter Methods

Filter methods select features based on their statistical relationship with the target variable.

They are generally independent of the machine learning model.

Common techniques include:

- Correlation
- Chi-Square Test
- ANOVA
- Mutual Information
- Variance Threshold

📓 Notebook:

[`filter-based-feature-selection.ipynb`](./filter-based-feature-selection.ipynb)

---

### 2. Wrapper Methods

Wrapper methods evaluate different subsets of features by training a machine learning model and selecting the subset that gives the best performance.

Common techniques include:

- Forward Selection
- Backward Elimination
- Recursive Feature Elimination (RFE)
- Sequential Feature Selection

📓 Notebook:

`wrapper-based-feature-selection.ipynb`

---

### 3. Embedded Methods

Embedded methods perform feature selection during the model training process.

The feature-selection process is built into the learning algorithm itself.

Common techniques include:

- Lasso Regression (L1 Regularization)
- Ridge Regression
- Decision Tree Feature Importance
- Random Forest Feature Importance

📓 Notebook:

`embedded-feature-selection.ipynb`

---

## 📂 Repository Structure

```text
Feature-Selection/
│
├── filter-based-feature-selection.ipynb
├── wrapper-based-feature-selection.ipynb
├── embedded-feature-selection.ipynb
│
└── README.md
