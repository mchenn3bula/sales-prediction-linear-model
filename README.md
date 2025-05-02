# 📈 Linear Regression Lab – Predicting Sales with Advertising Data

![Python](https://img.shields.io/badge/Python-Data%20Science-blue)
![ML Technique](https://img.shields.io/badge/ML%20Technique-Linear%20Regression-green)
![Visualization](https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-orange)

## 🧠 Project Overview

This notebook introduces **Linear Regression**, one of the core techniques in Machine Learning and Statistical Modeling. Using real-world advertising data, we predict **sales** based on **TV, Radio, and Newspaper** ad spending.

This lab is adapted from Chapter 3 of [An Introduction to Statistical Learning](https://www.statlearning.com/) and was developed as part of a data science module at NYU.

---

## 🎯 Goals

- Understand the basics of linear regression
- Analyze how advertising budgets impact product sales
- Learn to use Pandas, Seaborn, and Scikit-learn
- Visualize relationships and evaluate regression models

---

## 📊 Dataset Description

| Feature      | Description                        |
|--------------|------------------------------------|
| TV           | Budget spent on TV ads (in $1000s) |
| Radio        | Budget spent on Radio ads          |
| Newspaper    | Budget spent on Newspaper ads      |
| Sales        | Product sales (units sold)         |

Data source: `Advertising.csv`

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas**, **NumPy**
- **Scikit-learn** (LinearRegression)
- **Matplotlib**, **Seaborn**
- **Scipy** for statistical tools

---

## 📁 Project Structure

```

linear-regression-lab/
├── linear\_regression.ipynb       # Jupyter notebook with all code and answers
├── README.md                     # This file
└── Advertising.csv               # Source dataset (optional to upload)

````

---

## 🚀 Sample Workflow

```python
# Train a linear regression model
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X, y)
predictions = model.predict(X_test)
````

---

## 📌 Notes

* Questions are marked with `⏩` in the notebook.
* Submit your notebook via the official platform (not by email).
* This is **individual work**.

---

## 👨‍🏫 Credits

* Based on materials by: *ISL – Introduction to Statistical Learning*
* Instructor: *\[Course Instructor's Name, if known]*
* Notebook adapted and enhanced for GitHub

