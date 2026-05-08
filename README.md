# Car_Eval_Classification
This project classifies car acceptability using Python and machine learning. The workflow includes preprocessing and encoding raw Kaggle data, training multiple classification models (Random Forest, Decision Tree), and evaluating performance using standard classification metrics.


## DISCLAIMER 
This project uses a 3rd party data source from Kaggle. Data from this file may be inaccurate or missing. This is solely to demonstrate skills of Python, Pandas, and Scikit-learn.

## Data Source
The dataset used for this project was obtained from Kaggle:
https://www.kaggle.com/datasets/kanyianalyst/car-evaluation-dataset?select=car+evaluation_with.csv

## Applications Used / Needed to Replicate
- Python (requirements.txt) has needed packages.
- Jupyter Notebook or any Python IDE

## Process of Project
1. **Data Collecting & Preprocessing (Python)**
- Downloaded the raw data source from Kaggle.
- Using Pandas, read in the CSV file in Python.
- Identified and encoded categorical features using label encoding to prepare data for modeling.
- Verified no null values were present in the dataset.

2. **Model Training & Evaluation (Scikit-learn)**
- Split the data into training and testing sets.
- Trained multiple classification models including Decision Tree and Random Forest.
- Evaluated each model using accuracy, precision, recall, and F1-score to determine usability.
- Both models achieved above 98% accuracy on the test set.

3. **Visualizing Results**
- Generated confusion matrices to visualize model predictions against actual labels.
- Produced classification reports to summarize performance across all classes.

## Findings
1. The dataset was well structured with no missing values, making preprocessing straightforward and allowing more focus on model tuning and evaluation.
2. Both the Decision Tree and Random Forest models achieved above 98% accuracy, confirming strong usability across both approaches.
3. Precision, recall, and F1-score remained consistently high across all four acceptability classes, suggesting both models generalize well rather than overfitting to the training data.
