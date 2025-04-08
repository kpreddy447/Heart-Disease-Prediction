# Heart Disease Prediction: Model Evaluation and Performance Analysis

## Overview

This project is dedicated to predicting the likelihood of heart disease using machine learning algorithms. The dataset used for this project includes clinical and demographic features related to heart disease risk factors, and various classification models are evaluated based on their performance in predicting the presence of heart disease.

Several machine learning models were implemented, including:
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Ridge Classifier

The goal of this project is to evaluate and compare the performance of these models using key metrics like accuracy, precision, recall, F1-score, and AUC (Area Under the Curve). Additionally, the models are assessed using confusion matrices, ROC (Receiver Operating Characteristic) curves, and Precision-Recall curves.

## Features

- **Multiple classification models** tested for heart disease prediction.
- **Evaluation metrics** including accuracy, precision, recall, F1-score, ROC curve, and Precision-Recall curve.
- **Confusion Matrix** for understanding model predictions vs actual values.
- Visualizations for a better understanding of the model performance.

## Table of Contents

- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [File Structure](#file-structure)
- [License](#license)

## Technologies

This project utilizes the following technologies:

- **Python** (Programming Language)
- **NumPy** (For numerical operations)
- **Pandas** (For data manipulation and preprocessing)
- **Matplotlib** (For data visualization)
- **Seaborn** (For statistical data visualization)
- **Scikit-Learn** (For machine learning models and metrics)
- **SciPy** (For statistical analysis)

You can install the required libraries via `pip` using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
```

## Getting Started

### Prerequisites

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. **Download the dataset**: Ensure that the dataset is placed in the appropriate directory or adjust the dataset path in the script accordingly.

    The dataset used for this project contains the following features:
    - Age
    - Sex
    - Chest pain type
    - Resting blood pressure
    - Serum cholesterol
    - Fasting blood sugar
    - Electrocardiographic results
    - Maximum heart rate achieved
    - Exercise induced angina
    - Oldpeak depression induced by exercise relative to rest
    - Slope of the peak exercise ST segment
    - Number of major vessels colored by fluoroscopy
    - Thalassemia

### Running the Project

Once the dependencies are installed and the dataset is in place, run the following command to execute the script and train/evaluate the models:

```bash
python heart_disease_prediction.py
```

This will load the dataset, preprocess the data, train the models, evaluate them on multiple metrics, and display visualizations for confusion matrices, ROC curves, and Precision-Recall curves.

## Usage

Once the script is executed, the following outputs will be available:
- **Model Evaluation**: A detailed evaluation of each model, including metrics such as accuracy, precision, recall, F1-score, and AUC.
- **Confusion Matrix**: Visual representation of model performance in terms of true positive, false positive, true negative, and false negative predictions.
- **ROC Curve**: Graph showing the true positive rate vs. false positive rate for each model.
- **Precision-Recall Curve**: Evaluation of the models' precision and recall across different thresholds.
