# 🔋 Battery Remaining Useful Life (RUL) Prediction

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-Model-green.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## Overview

This project predicts the **Remaining Useful Life (RUL) of batteries** using Machine Learning regression models. The goal is to estimate how much useful life remains in a battery based on operational and health-related parameters.

A deployed web version of the model is also available for demonstration:

https://battery-rul-predictor.streamlit.app/

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Outlier detection and handling
- Feature scaling and transformation
- Training multiple regression models
- Model evaluation and comparison
- Feature importance analysis
- Final battery RUL prediction model

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Streamlit

---

## Project Structure

```text
Project Folder/
│
├── Project.ipynb
├── Battery_RUL.csv
├── battery_rul_et_model.pkl
├── power_transformer.pkl
└── README.md
```

---

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
```

Activate environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost streamlit joblib
```

---

## How to Run the Project

### Step 1: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 2: Open File

Open:

```
Project.ipynb
```

### Step 3: Run the Notebook

Run all cells sequentially from top to bottom.

---

## What the Notebook Does

When executed, the notebook will:

- Load the dataset (`Battery_RUL.csv`)
- Perform data cleaning and preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Handle outliers and transform features
- Train multiple machine learning models
- Evaluate models using performance metrics
- Select the best model
- Save trained model files (`.pkl`)
- Generate predictions for Battery RUL

---

## Machine Learning Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Extra Trees Regressor
- AdaBoost Regressor
- Support Vector Regressor (SVR)
- K-Nearest Neighbors (KNN)
- XGBoost Regressor

---

## Evaluation Metrics

Models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Saved Model Files

After training, the following files are generated:

```
battery_rul_et_model.pkl
power_transformer.pkl
```

These files can be used later to load the model and make predictions without retraining.

---

## Live Demo

Try the deployed application here:

https://battery-rul-predictor.streamlit.app/

---

## Author

**Muhammad Talha**
