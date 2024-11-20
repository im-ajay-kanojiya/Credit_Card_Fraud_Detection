# Credit Card Fraud Detection

This project focuses on detecting fraudulent transactions in credit card data using machine learning. The dataset used is highly imbalanced, and techniques such as under-sampling were employed to balance the data distribution.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Approach](#approach)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Conclusion](#conclusion)

## Introduction
Credit card fraud detection is a significant problem in the financial industry. This project uses supervised machine learning models to classify transactions as either normal or fraudulent.

## Dataset
The dataset contains credit card transaction details, where:
- **0**: Normal transactions.
- **1**: Fraudulent transactions.  
Key statistics:
- Number of fraudulent transactions: **492**
- The dataset is highly imbalanced, requiring preprocessing to balance the classes.

## Approach
1. **Data Preprocessing**:
   - Analyzed the dataset for missing or inconsistent values.
   - Balanced the dataset using **under-sampling** to ensure equal representation of normal and fraudulent transactions.

2. **Feature and Target Split**:
   - Split the data into independent features and the target variable.

3. **Train-Test Split**:
   - Divided the data into training and testing sets to evaluate the model performance effectively.

## Modeling
Implemented the following steps:
- **Model**: Logistic Regression
- **Training**: Built and trained the logistic regression model on the balanced dataset.

## Evaluation
Evaluated the model using metrics like:
- **Accuracy Score**: Indicates the overall performance of the model.

## Results
- The logistic regression model demonstrated [mention accuracy or any notable performance metric if available].

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - `NumPy`
  - `Pandas`
  - `scikit-learn`

## Usage
1. Clone the repository.
2. Install the dependencies using `pip install -r requirements.txt`.
3. Run the notebook `Project_10_Credit_Card_Fraud_Detection.ipynb` to replicate the results.

## Conclusion
This project highlights the challenges of imbalanced datasets and the importance of preprocessing to improve model performance. Logistic regression was effective in detecting fraudulent transactions with balanced data....

