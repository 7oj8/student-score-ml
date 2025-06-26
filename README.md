# Student Score Prediction

## Dataset  

**Students Performance in Exams** — Kaggle 
- ( included in each folder )

## Objective  

Analyze student-performance data and build models that predict exam results while revealing the factors that most influence academic success.

## What I Did  

- **Loaded and Explored the Data:** Imported the CSV into a pandas DataFrame, checked data types, missing values, and basic statistics.  
- **Cleaned and Feature-Engineered:** Filled or dropped nulls, label-encoded categorical variables, and created features such as total score, average score, and a pass/fail flag.  
- **Built Predictive Models:**
  
  - *Simple Linear Regression* to predict total score from study hours.  
  - *Multiple Linear Regression* using all available features.  
  - *Logistic Regression* to classify pass vs. fail.
    
- **Evaluated Performance:** Used MAE, RMSE, and R² for regression models; accuracy, precision, recall, and F1 score for classification.  
- **Visualized Findings:** Plotted score distributions, study-hours vs. score scatter plots, and feature-importance charts with Matplotlib.

## Tools Used  
- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook / Google Colab
