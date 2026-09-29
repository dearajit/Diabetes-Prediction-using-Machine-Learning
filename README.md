# Diabetes Prediction using Machine Learning

## Project Overview

This project uses machine learning classification algorithms to predict whether a patient is likely to have diabetes based on diagnostic and health-related features.

The project demonstrates a complete machine learning workflow, including data exploration, data cleaning, handling missing values, feature scaling, model training, model evaluation, and individual patient prediction.

## Dataset

The project uses a diabetes dataset stored in `pima-dataset.xlsx`.

The features used for prediction include:

* Number of Pregnancies
* Glucose Concentration
* Diastolic Blood Pressure
* Insulin
* BMI
* Diabetes Pedigree Function
* Age
* Skin Thickness

The target variable is:

* `diabetes`

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* Excel / XLSX Dataset

## Machine Learning Workflow

The project follows these steps:

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check zero values and missing measurements
5. Prepare features and target
6. Split the dataset into training and testing sets
7. Handle missing values using mean imputation
8. Apply feature scaling using StandardScaler
9. Train machine learning models
10. Evaluate model performance
11. Compare model accuracy
12. Generate a confusion matrix
13. Perform an individual patient prediction

## Machine Learning Models

Three classification algorithms were implemented:

### 1. Gaussian Naive Bayes

Used as a baseline classification model for predicting diabetes outcomes.

### 2. Random Forest Classifier

An ensemble learning method based on multiple decision trees.

### 3. K-Nearest Neighbors (KNN)

A classification algorithm that predicts an outcome based on the similarity between observations.

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Classification Report
* Confusion Matrix

The existing notebook results show approximately **75.32% test accuracy for the Random Forest model**.

## Model Comparison

The project compares the test accuracy of:

* Naive Bayes
* Random Forest
* KNN

A visualization is also created to compare their test performance.

## Individual Patient Prediction

The project also demonstrates prediction for an individual patient using the trained Random Forest model.

The same preprocessing steps used during model training are applied before generating the prediction.

## Project Structure

```text
Diabetes-Prediction-using-Machine-Learning/
│
├── Diabetes_Prediction_using_Machine_Learning.ipynb
├── pima-dataset.xlsx
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project directory

```bash
cd Diabetes-Prediction-using-Machine-Learning
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Diabetes_Prediction_using_Machine_Learning.ipynb
```

Run the notebook cells from top to bottom.

## Disclaimer

This project is intended for educational and machine learning demonstration purposes. It is not a medical diagnostic tool and should not be used to make medical decisions.

## Author

**Ajit Chingale**

GitHub: Add your GitHub profile link here "https://github.com/dearajit"

LinkedIn: Add your LinkedIn profile link here "https://www.linkedin.com/in/ajit-chingale-9ab41b281/"
