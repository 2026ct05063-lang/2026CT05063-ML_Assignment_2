# 2026CT05063-ML_Assignment_2
# Machine Learning Assignment 2 – Adult Census Income Classification
**Student ID:** 2026CT05063  
**Repository:** https://github.com/2026ct05063-lang/2026CT05063-ML_Assignment_2

**BITS Pilani | M.Tech – Machine Learning**

## 1. Project Overview

This project focuses on developing supervised machine learning classification models to predict whether an individual's annual income exceeds $50,000 using the Adult Census Income dataset.

Five machine learning algorithms are implemented and evaluated using multiple classification performance metrics.

## 2. Project Objectives

- Understand and analyze the Adult Census Income dataset.
- Perform data cleaning and exploratory data analysis (EDA).
- Apply appropriate data preprocessing techniques.
- Implement five supervised classification algorithms.
- Evaluate and compare model performance.
- Identify the best-performing classification model.

## 3. Dataset Description

The Adult Census Income dataset contains demographic and employment-related information used to predict an individual's income category.

Note: The Dataset is take from UCI repository

**Dataset characteristics after cleaning:**

| Parameter | Value |
|---|---:|
| Total Records | 48,790 |
| Total Columns | 15 |
| Input Features | 14 |
| Target Variable | income |
| Target Classes | 2 |
| Training Records | 39,032 |
| Testing Records | 9,758 |

**Target variable:**
- `0` – Income less than or equal to $50K
- `1` – Income greater than $50K

## 4. Data Preprocessing

The following preprocessing activities were performed:

1. Dataset loading and initial inspection.
2. Identification of missing values.
3. Duplicate record identification and removal.
4. Target variable normalization and binary encoding.
5. Numerical and categorical feature identification.
6. Categorical feature encoding.
7. Numerical feature scaling.
8. Stratified 80:20 train-test split.

The final preprocessed feature matrix contained 105 features.

## 5. Machine Learning Algorithms

The following five classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Gaussian Naive Bayes
5. Random Forest Classifier

## 6. Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Matthews Correlation Coefficient (MCC)

## 7. Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC | MCC |
|---|---:|---:|---:|---:|---:|---:|
| Logistic Regression | 0.8520 | 0.7304 | 0.6053 | 0.6620 | 0.9081 | 0.5724 |
| Decision Tree | 0.8214 | 0.6242 | 0.6378 | 0.6310 | 0.7587 | 0.5132 |
| KNN | 0.8389 | 0.6835 | 0.6092 | 0.6442 | 0.8667 | 0.5420 |
| Naive Bayes | 0.5990 | 0.3672 | 0.9336 | 0.5271 | 0.8174 | 0.3736 |
| Random Forest | **0.8558** | 0.7289 | 0.6331 | **0.6777** | 0.9050 | **0.5878** |

## 8. Results and Observations

- Random Forest achieved the highest accuracy of 85.58%.
- Random Forest achieved the highest F1 Score of 0.6777.
- Random Forest achieved the highest MCC of 0.5878.
- Logistic Regression achieved the highest ROC-AUC of 0.9081.
- Naive Bayes achieved the highest recall of 0.9336.

Based on the combined accuracy, F1 Score and MCC results, Random Forest was identified as the best overall-performing model.

## 9. Technologies and Libraries

**Programming Language:** Python

**Development Environment:** Google Colab

**Libraries:**
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 10. Repository Contents

- Jupyter Notebook containing data analysis, preprocessing, model training and evaluation.
- `requirements.txt` containing the project dependencies.
- `README.md` containing project documentation.

Additional model files, test data and evaluation results will be included in the repository.

## 11. Installation and Execution

Clone the repository:

```bash
git clone https://github.com/2026ct05063-lang/2026CT05063-ML_Assignment_2.git
```

Navigate to the project directory:

```bash
cd 2026CT05063-ML_Assignment_2
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the Jupyter Notebook using Google Colab or a compatible Jupyter environment and execute the notebook cells sequentially.

## 12. Conclusion

This assignment demonstrates the application of supervised machine learning algorithms for binary income classification.

Five classification algorithms were implemented and evaluated using six performance metrics.

Random Forest demonstrated the strongest overall performance based on accuracy, F1 Score and Matthews Correlation Coefficient, while Logistic Regression achieved the highest ROC-AUC.

The experiment highlights the importance of data preprocessing, model evaluation and comparative analysis in developing effective machine learning classification solutions.

---
