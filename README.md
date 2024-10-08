# Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions using machine learning models. It aims to help reduce the occurrence of credit card fraud by classifying transactions as either legitimate or fraudulent based on historical transaction data.

## Project Structure

- data/: Contains datasets used for training and testing.
- notebooks/: Jupyter notebooks showcasing the data analysis, feature engineering, and model building.
- src/: Python scripts for data preprocessing, model training, and evaluation.
- results/: Model evaluation metrics, confusion matrix, and performance reports.

## Features

- *Data Preprocessing:* Handling imbalanced data using techniques like oversampling (SMOTE), undersampling, or class-weighting.
- *Modeling:* Trained models like Logistic Regression, Random Forest, XGBoost, etc.
- *Evaluation:* Evaluated on metrics like accuracy, precision, recall, F1-score, and AUC-ROC curve.

## Requirements

To run the project, install the necessary dependencies using:

```bash
pip install -r requirements.txt# Credit-Card-Fraud-Prediction

## Usage

1. Clone this repository:
   bash
   git clone https://github.com/yourusername/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection
   

2. Run the data preprocessing script:
   bash
   python src/data_preprocessing.py
   

3. Train the model:
   bash
   python src/train_model.py
   

4. Evaluate the model:
   bash
   python src/evaluate_model.py
   
