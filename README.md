
---

# Titanic - Machine Learning from Disaster

This repository contains a machine learning project using the Titanic dataset to predict passenger survival.

## Overview

The project aims to predict survival based on features like age, gender, and class. Key tasks include:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Model training and evaluation

## Dataset

The data is sourced from the [Kaggle Titanic competition](https://www.kaggle.com/c/titanic/data):
- `train.csv`: For training the model
- `test.csv`: For making predictions

## Models

Several models were tested, with AdaBoost providing the best accuracy:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

Final accuracy using AdaBoost was 0.82.

## Installation

1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/titanic-machine-learning.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:  
   ```bash
   jupyter notebook titanic-machine-learning.ipynb
   ```

## Future Work

- Explore deep learning
- Further tune hyperparameters
- Generalize survival models to other contexts

---
