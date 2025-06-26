# Student Score Prediction – Machine-Learning Project

## Dataset
* **Source** Student Performance Data Set (UCI / Kaggle)  
  <https://www.kaggle.com/datasets/spscientist/students-performance-in-exams>  
* **Scope** 1 000 secondary-school students, with features such as study hours, parental education, lunch type, test preparation, and scores in maths, reading and writing.

## Objective
Predict students’ academic results and understand which factors influence performance.

## What I Did
* **Loaded & Explored the Data**  
  * Imported the CSV into a pandas DataFrame.  
  * Inspected column types, checked for duplicates and missing values, reviewed descriptive stats.
* **Cleaned & Feature-Engineered**  
  * Filled / dropped nulls, label-encoded categoricals.  
  * Created numerical indicators (e.g. total score, average score) and binary targets (pass / fail ≥ 50).  
  * Normalised numeric inputs where required.
* **Modelled Performance**  
  * **Simple Linear Regression** – predict total score from study hours.  
  * **Multiple Linear Regression** – include all available features.  
  * **Classification** – logistic regression and random forest to classify pass vs. fail.
* **Evaluated Models**  
  * Regression: MAE, RMSE, R².  
  * Classification: accuracy, precision, recall, F1.  
  * Cross-validation to check robustness.
* **Visualised Findings**  
  * Histograms of score distributions.  
  * Scatter plots of study hours vs. score.  
  * Feature-importance bar chart for the random-forest model.

## Tools Used
* Python 3.9  
* pandas, numpy  
* scikit-learn  
* matplotlib  
* Jupyter Notebook / Google Colab
