# Assignment16

## Assignment 16: SVM, Trees, Ensembles, Validation & Unsupervised Learning

# Problem Statement
You are working as a Machine Learning Engineer. In this assignment, you will implement advanced ML algorithms, understand model validation strategies, apply ensemble learning.
This assignment covers:
- Support Vector Machine (SVM)
- Decision Tree Algorithm
- Train vs Validation vs Test & Cross-Validation
- Ensemble Learning (Bagging vs Boosting)
- Random Forest (Bagging)

_______________________________________________________________

# PART 1 - Advanced Supervised Algorithms
_______________________________________________________________

## Task 1: Support Vector Machine (SVM)
1. Select a classification dataset.
2. Split into train and test sets.
3. Train an SVM classifier using SVC.
4. Experiment with:
- Linear kernel
- RBF kernel
5. Compare accuracy of both kernels.

## Task 2: Decision Tree Algorithm
1. Train a Decision Tree Classifier.
2. Visualize the tree structure (depth limited).
3. Train models with:
- Low max_depth (underfitting)
- High max_depth (overfitting)
4. Compare train vs test accuracy.
_____________________________________________________________

# PART 2 — Model Validation & Cross-Validation
_____________________________________________________________

## Task 3: Train vs Validation vs Test Split
1. Split data into:
o Training set
• Validation set
• Test set
2. Train model on training data.
3. Tune one simple parameter using validation set.
4. Evaluate final model on test set.

## Task 4: Cross-Validation
1. Apply K-Fold Cross Validation (k=5).
2. Compute average accuracy.
3. Compare single train-test accuracy vs cross-validation accuracy.

_____________________________________________________________

PART 3 - Ensemble Learning
_____________________________________________________________

## Task 5: Bagging vs Boosting (Conceptual + Practical)
1. Briefly explain:
    - Bagging
    - Boosting
2. Train:
    - Bagging Classifier
    - AdaBoost Classifier
3. Compare their performance.


## Task 6: Random Forest (Bagging)
1. Train a Random Forest Classifier.
2. Compare performance with:
    - Single Decision Tree
    - Bagging Classifier
3. Print feature importance.