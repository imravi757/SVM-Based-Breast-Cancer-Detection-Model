# Breast Cancer Classification using Support Vector Machines (SVM)

## Project Overview
This project implements a machine learning model to classify breast tumors as malignant or benign using Support Vector Machines (SVM). The model achieves 94.7% accuracy on the test set, demonstrating strong predictive performance for this critical healthcare application.

## Technical Details
- **Algorithm**: Linear SVM implemented via scikit-learn
- **Dataset**: Breast Cancer Wisconsin Diagnostic Dataset (569 samples, 30 features)
- **Features**: Includes tumor characteristics like radius, texture, perimeter, area, and smoothness
- **Model Performance**: 94.7% accuracy on held-out test data

## Implementation Highlights
1. **Data Preprocessing**:
   - Standard train-test split (90-10 ratio)
   - Feature analysis and selection

2. **Model Development**:
   - SVM with linear kernel implementation
   - Hyperparameter tuning (default parameters used)

3. **Evaluation**:
   - Accuracy metric calculation
   - Prediction vs actual comparison
   - Model serialization using pickle

## How to Use
1. Clone repository
2. Install requirements (Python 3.x, scikit-learn, pandas, numpy)
3. Run Jupyter notebook `Breast_cancer_SVM.ipynb`

## Potential Applications
- Medical diagnostic support systems
- Healthcare machine learning pipelines
- Educational example of SVM implementation

This project demonstrates my skills in:
- Machine learning with scikit-learn
- Medical data analysis
- Model evaluation and deployment
- Python programming for data science

Contributions and suggestions are welcome!
