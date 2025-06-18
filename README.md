
# Titanic - Machine Learning from Disaster

This repository contains a solution to the classic [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic), which challenges participants to use machine learning to predict which passengers survived the Titanic shipwreck.

## 📘 Project Overview

The goal of this project is to build a predictive model that can determine whether a passenger survived the disaster, based on features such as age, sex, ticket class, and more.

## 🔍 Contents

- **Data Exploration and Cleaning:** Basic inspection and preprocessing of the dataset including handling missing values and feature engineering.
- **Exploratory Data Analysis (EDA):** Visual analysis to understand the relationships between variables and the target.
- **Feature Engineering:** Transformation of categorical features, creation of new variables (e.g., family size), and binning of continuous variables.
- **Modeling:** Multiple machine learning models were trained and evaluated:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Decision Tree
  - Gradient Boosting Classifier
- **Evaluation:** Cross-validation and model performance comparison using accuracy scores.
- **Submission:** Generating a submission file with predictions for the test dataset.

## 📂 Files

- `titanic_competition.ipynb` – Jupyter Notebook containing the full pipeline: data loading, preprocessing, model training, evaluation, and submission generation.

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

## 🚀 Getting Started

1. Clone this repository.
2. Install the required dependencies listed below.
3. Open the notebook in Jupyter and run all cells.

### Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Data

Download the datasets from the [Kaggle Titanic competition page](https://www.kaggle.com/competitions/titanic/data) and place them in the same directory as the notebook:
- `train.csv`
- `test.csv`

## 📈 Results

The model with the best performance in this notebook was the Gradient Boosting Classifier, achieving a strong cross-validation score.

## 📬 Submission

The notebook creates a `submission.csv` file containing passenger IDs and survival predictions, ready for upload to Kaggle.

## 🙌 Acknowledgments

Inspired by the Titanic Kaggle competition and numerous publicly available notebooks and discussions on the Kaggle platform.
