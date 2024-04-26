# Integrating Ayurvedic Principles with Machine Learning for Pre-diabetes Classification

This project presents a novel methodology for pre-diabetes diagnosis by combining Ayurvedic principles with machine learning techniques. By leveraging questionnaire-based assessments and machine learning algorithms, a classification model is developed to identify pre-diabetic individuals.

## Overview

The study collected data from 165 participants through Google Forms, analyzing responses to 23 questions related to Ayurvedic principles and pre-diabetes symptoms. The methodology involved data preprocessing, model training, and evaluation using classification algorithms such as logistic regression, support vector machine, decision tree, random forest, and AdaBoost.

## Methodology

1. **Data Collection**: A questionnaire was designed in consultation with an Ayurvedic expert, and data was collected from 165 participants using Google Forms.
2. **Data Preprocessing**: Missing data, outliers, and data distribution were handled using techniques like removing null values, label encoding, interquartile range rule, and SMOTE for data amplification.(encoded.csv is a pre-proceesed file)
3. **Model Training and Evaluation**: Various classification models, including logistic regression, support vector machine, decision tree, random forest, and AdaBoost, were trained and evaluated using metrics like precision, recall, accuracy, and F1-score.
4. **Result Visualization**: Techniques such as ROC curves, precision-recall curves, confusion matrices, and learning curves were utilized to interpret the results.

## Results

The AdaBoost classifier achieved the highest accuracy, demonstrating promise for pre-diabetes classification. The study highlights the potential of integrating Ayurvedic principles with modern machine learning approaches for healthcare diagnostics, offering a non-invasive and efficient means of pre-diabetes detection.

## Future Scope

Future research could explore integrating prakriti analysis data into the framework, further enhancing its diagnostic capabilities.

## Dataset and Implementation

The dataset and the baseline implementation can be found in the following GitHub repository: https://github.com/preethamvooturi/prediabatic_classification.git
