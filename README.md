# SVM-classification-project
Support Vector Machine implementation using Python and Scikit-learn
## Overview
This project develops and evaluates Support Vector Machine (SVM) models using both from-scratch implementation and Scikit-learn. It explores the impact of kernel selection (linear and RBF) and hyperparameter tuning on classification performance using the Iris dataset.

## Features
- Developed and evaluated Linear and RBF Kernel SVM models for multi-class classification
- Performed hyperparameter tuning (C, gamma) to optimise model performance
- Applied 5-fold cross-validation to improve model generalisation
- Assessed performance using accuracy metrics and confusion matrix analysis

## Tech Stack
Python, NumPy, Pandas, Scikit-learn, Matplotlib

## Results
### Model Performance
The model achieved an accuracy of 97–100% on the Iris dataset, demonstrating strong classification performance across all classes.

### Hyperparameter Tuning Results
<img width="626" height="466" alt="image" src="https://github.com/user-attachments/assets/78ff3e27-6e54-472c-9295-3d3b2c6bec4e" />

### Confusion Matrix
<img width="1222" height="515" alt="image" src="https://github.com/user-attachments/assets/e57547c7-1e52-4d0c-9674-62e036355736" />

### Decision Boundary Visualization
<img width="821" height="505" alt="image" src="https://github.com/user-attachments/assets/a87cacbf-c4c1-4bf5-939a-c7cc39fff37b" />

## Key Insight
The RBF kernel demonstrated improved performance in handling non-linear class boundaries compared to the linear SVM, highlighting the importance of kernel selection in real-world classification problems.

## Author
Deepanshi Bansal
