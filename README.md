# ECG Classification for Heart Disease Detection

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Features](#dataset-features)
3. [Our Approach](#our-approach)
4. [Model Performance](#model-performance)
5. [Comparison with Previous Work](#comparison-with-previous-work)
6. [Results](#results)
7. [Acknowledgements](#acknowledgements)

## Introduction

This project focuses on developing a machine learning model for ECG classification to detect heart disease. By integrating machine learning with medical data, we aim to analyze ECG data effectively and improve patient treatment. Our approach allows for faster and more cost-effective predictions, assisting both patients and doctors in diagnosing heart diseases more efficiently than traditional methods.

## Dataset Features

Our dataset includes 14 key features for heart disease prediction:

1. Age (in years)
2. Sex (gender of the person)
3. Chest Pain (Cp)
4. Resting Blood Pressure (Trestbps, in mmHg)
5. Serum Cholesterol level (Chol, in mg/dl)
6. Fasting Blood Sugar (Fbs, 1 if true, 0 if false)
7. Resting Electrocardiograph Results (Restecg)
8. Maximum Heart Rate Achieved during exercise (Thalach)
9. Exercise-Induced Angina (Exangs)
10. ST Depression induced by exercise relative to rest (Old Peak)
11. ST Segment Slope during peak exercise (ST Slope)
12. Number of Major Vessels colored by Fluoroscopy (Ca)
13. Thalassemia (Thal, defect type)
14. Target (presence of heart disease, 1 if true, 0 if false)

## Our Approach

Our classification process involves the following steps:

1. Data Preprocessing:
   - Examine the dataset structure and dimensions
   - Check data types of attributes
   - Handle missing or null values
   - Calculate key statistical measures (mean, standard deviation)

2. Model Training:
   We employ six machine learning algorithms:
   - Logistic Regression (LR)
   - K-Nearest Neighbors (K-NN)
   - Naive Bayes
   - Support Vector Machine (SVM)
   - XG-Boost
   - Neural Network (with Adam optimizer)

## Model Performance

Our models showed varying levels of performance:

- XG-Boost achieved the highest accuracy at 98.54%, with 100% precision, 98.7% sensitivity, and 100% specificity.
- The Neural Network (with Adam optimizer) showed strong performance with 94.48% accuracy, 100% precision, 91.28% sensitivity, and 100% specificity.
- Logistic Regression performed well with 87.01% accuracy, 84.7% precision, 92% sensitivity, and 81.3% specificity.
- K-Nearest Neighbors achieved 84.09% accuracy, 81.65% precision, 86.58% sensitivity, and 81.76% specificity.
- Naive Bayes resulted in 81.49% accuracy, 76.44% precision, 89.26% sensitivity, and 74.21% specificity.
- SVM showed 80.84% accuracy, 76.47% precision, 87.25% sensitivity, and 74.84% specificity.

## Comparison with Previous Work

Our model demonstrates improvements in accuracy for several classifiers compared to previous studies:

- Logistic Regression: Improved from 86.89% to 87.13%
- K-Nearest Neighbors: Significant improvement from 77.70% to 84.09%
- XG-Boost: Substantial improvement from 91.80% to 98.54%
- Neural Network: Considerable improvement from 83.50% to 94.48%

While our Naive Bayes and SVM models showed slightly lower accuracy compared to previous work (86.29% to 81.49% and 84.00% to 80.84% respectively), the overall performance of our suite of models represents a significant step forward in ECG-based heart disease detection.

## Results

Our automatic model for predicting heart disease using six ML classifiers achieved an average accuracy of 87.74%. The XG-Boost algorithm yielded the highest accuracy at 98.54%. This approach allows for faster and more cost-effective predictions, assisting both patients and doctors in diagnosing heart diseases more efficiently than traditional methods.

## Acknowledgements

## Team Members
This project was conducted as part of the Machine Learning research work at IIIT Bhopal, under the guidance of Prof. Bhupendra Singh. Special thanks to the following team members for their contributions:

- **Harsh Shivhare**
- **Shivansh Vikram Singh**


## How to Use

[Instructions on how to set up and run the project would go here. As this information wasn't provided, you may want to add details about requirements, installation steps, and usage examples when available.]

## Contributing

[Information about how others can contribute to this project would go here. This might include guidelines for submitting issues, making pull requests, or coding standards.]

## License

[Information about the project's license would go here. If a specific license hasn't been chosen, you may want to consider adding one to clarify how others can use and distribute your code.]