# Machine Learning 10 — Decision Tree Student Performance

## Overview

This project uses a Decision Tree classifier to predict whether a student will **Pass** or **Needs Support** from study habits, attendance, previous exam performance, assignments, sleep, and class participation.

The notebook loads the student dataset, separates features from the `Result` target, splits it into training and test sets with stratification, and trains a constrained Decision Tree to reduce overfitting. It evaluates the model with accuracy, a classification report, a confusion matrix, feature importance, and a visualized decision tree.

## Files

- `Decision_Tree_student_performance_score.ipynb` — model training and evaluation notebook
- `Decision_Tree_Student_Performance_Dataset.csv.xls` — student performance dataset

## Tools

Python, Pandas, Matplotlib, and Scikit-learn.

## Run

```bash
pip install pandas matplotlib scikit-learn
jupyter notebook
```

Open `Decision_Tree_student_performance_score.ipynb` and run all cells.

## Model

The `DecisionTreeClassifier` uses:

- Maximum depth: `4`
- Minimum samples per leaf: `8`
- Random state: `42`

The data is split 80% for training and 20% for testing, with class distribution preserved through stratification.
