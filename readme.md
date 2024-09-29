
# Predictive modelling for Sydney restaurant

This repository contains a classification analysis, a linear regression model, a SGD regression model and using three machine learning models:
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Contents
- The code compares the performance of the three models on a dataset with imbalanced classes.
- It includes confusion matrices for each model, performance metrics like True Positives, True Negatives, False Positives, and False Negatives.

### Files
- `Assi1.ipynb`: The Jupyter notebook with the implementation of the models, training, testing, and evaluation, including confusion matrices and accuracy calculations.

## How to Run the Code

1. **Install the required dependencies:**
   - You need Python and some key libraries like `scikit-learn`, `matplotlib`, `seaborn`, and `pandas`. 

2. **Open the notebook:**
   - You can open the `Assi1.ipynb` as Jupyter notebook.

3. **Run the notebook:**
   - Once the notebook is open, press runall.

## Expected Results

Upon running the code, the user will observe the following:
1. **Confusion Matrices** for each model (Random Forest, KNN, SVM).
2. **Performance metrics** such as accuracy, True Positives, False Positives, True Negatives, and False Negatives for each model.
3. **Visualizations** in the form of heatmaps for each confusion matrix to make the classification performance easy to interpret.

## Key Observations
- **Random Forest** provides the best classification accuracy with no misclassification.
- **SVM** follows closely with minimal errors.
- **KNN** has relatively more misclassifications but still shows decent performance on the dataset.
