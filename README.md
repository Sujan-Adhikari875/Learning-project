# Learning-project

# Classification Model Comparison

## Overview

This project compares the performance of multiple machine learning classification algorithms on the Iris dataset. The notebook demonstrates the complete machine learning workflow, from data preprocessing and exploratory data analysis (EDA) to model training, hyperparameter tuning, and performance evaluation.

The primary objective is to identify the best-performing classification model by comparing various evaluation metrics.

---

## Dataset

* **Dataset:** Iris Dataset
* **Target Variable:** Species
* **Features:**

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width

The Iris dataset is a well-known multiclass classification dataset containing three species of iris flowers.

---

## Project Workflow

1. Import required libraries
2. Load and inspect the dataset
3. Perform exploratory data analysis (EDA)
4. Data preprocessing and encoding
5. Split the dataset into training and testing sets
6. Feature scaling
7. Train multiple classification models
8. Hyperparameter tuning using GridSearchCV
9. Evaluate models using multiple metrics
10. Compare model performance


---

## Machine Learning Models

The following classification algorithms were implemented:

* Logistic Regression
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Gaussian Naive Bayes
* Random Forest Classifier
* Gradient Boosting Classifier
* AdaBoost Classifier

---

## Hyperparameter Tuning

Several models were optimized using **GridSearchCV** to determine the best combination of hyperparameters before evaluation.

---

## Evaluation Metrics

Each model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

These metrics provide a comprehensive comparison of model performance.

---

## Results

Among the tested models:

* Decision Tree
* Random Forest
* Gradient Boosting
* Gaussian Naive Bayes

achieved the highest classification accuracy of approximately **96.67%** on the test dataset.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```
Classification-Model-Comparison/
│
├── Classification Model Comparison.ipynb
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Apply the workflow to larger real-world datasets.
* Add ROC and AUC analysis for binary classification problems.
* Perform feature importance analysis.
* Implement cross-validation for more robust evaluation.
* Compare additional ensemble learning techniques.

---

## Author

**Adhikari Sujan**

This project was created for learning, practicing, and comparing machine learning classification algorithms using Python and Scikit-learn.
