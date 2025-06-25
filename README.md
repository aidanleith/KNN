## K-Nearest Neighbors (KNN)
This project implements a K-Nearest Neighbors (KNN) classifier using the scikit-learn digits dataset, which contains images of handwritten digits (0–9). The goal is to evaluate how the choice of k (number of neighbors) affects model performance, using F1 score as the evaluation metric.

# Features
- Loads digit image data and splits it into training and test sets.
- Displays random handwritten digit samples from the training set for visual inspection.
- Trains KNN classifiers using different k values (1, 3, 5, 7, 9).
- Calculates weighted F1 scores on the test set to compare classifier performance across k values.
- Shows qualitative predictions by displaying a few test images alongside predicted and true labels for each k.

  # Technologies
- Languages: Python
- Libraries and Frameworks: Pandas, NumPy, Matplotlib, scikit-learn
- Concepts: KNN, F1 Score, Classification, Model Evaluation
