# Penguin Species Classification

This project classifies Palmer penguin species (Adelie, Chinstrap, Gentoo) using physical measurements such as bill length, bill depth, flipper length, and body mass.

---

## Overview

- **Data Exploration:** Checked dataset structure, missing values, and class balance.  
- **Preprocessing:** Encoded categorical features, handled missing values, and split data into training/testing sets with stratification.  
- **Modeling:** Trained a baseline Decision Tree, evaluated with confusion matrix and classification metrics, visualized the tree.  
- **Hyperparameter Tuning:** Used GridSearchCV to optimize tree depth, splits, and leaf size, improving test accuracy from ~93% → ~96%.  
- **Interpretation:** Identified flipper length as the most important feature, checked model confidence on individual samples, visualized decision boundaries.

---

## Key Skills Learned

- Machine learning workflow (EDA → modeling → evaluation)  
- Decision Trees and feature importance  
- Hyperparameter tuning and cross-validation  
- Data preprocessing and encoding  
- Visualization of results and decision boundaries

---

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab

---

## How to Use

1. Clone the repo:  
```bash
git clone https://github.com/AymanBerri/ml-penguins-project.git
```
2. Open the notebook in Google Colab or Jupyter Notebook.

3. Run the cells to reproduce the analysis and plots.

---
## Key Skills Learned

- Machine learning workflow (EDA → modeling → evaluation)
- Decision Trees and feature importance
- Hyperparameter tuning and cross-validation
- Data preprocessing and encoding
- Visualization of results and decision boundaries
