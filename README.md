Handwritten Digit Image Classification

Overview

Handwritten digit recognition is a multi-class classification problem in computer vision and machine learning, with applications like postal mail sorting and form digitization.<br>
This project demonstrates the implementation and evaluation of three ML models on the MNIST dataset.

Objectives

Train and evaluate the following machine learning models:<br>
K-Nearest Neighbors (KNN)<br>
Artificial Neural Networks (ANN)<br>
Random Forest (RF)<br>
Develop a user-friendly interface to classify handwritten digits from uploaded images.<br>
Visualize prediction confidence and evaluate model performance.
Dataset

Initial Dataset
Locally stored MNIST dataset in CSV format.<br>
Challenges included manual reshaping, normalization, and scaling.<br>
Transition to TensorFlow’s Built-in MNIST Dataset
Preprocessed and standardized 28x28 grayscale images.<br>
Improved reliability and reduced preprocessing complexity.<br>
Enabled image augmentation for better generalization.<br>
Models and Methodology

K-Nearest Neighbors (KNN)
Instance-based learning with majority voting among k-nearest neighbors.<br>
Pros: Simple, effective for small datasets.<br>
Cons: Computationally expensive for large datasets.<br>
Artificial Neural Networks (ANN)
Two hidden layers with 128 and 64 neurons.<br>
Uses ReLU and softmax activation functions.<br>
Pros: High accuracy, capable of learning complex patterns.<br>
Cons: Computationally intensive, prone to overfitting.<br>
Random Forest (RF)
Ensemble learning with 300 decision trees and max depth of 30.<br>
Pros: Robust, handles noise well, provides feature importance.<br>
Cons: Computationally heavy for large datasets.<br>
Implementation Details

Data Preprocessing:<br>
Flatten MNIST images into vectors (784 features).<br>
Normalize pixel values (0–255 → 0–1).<br>
Prediction Interface:<br>
Upload images and choose the model (KNN, ANN, or RF) for predictions.<br>
Preprocess images into MNIST-compatible formats (28x28 grayscale).<br>
Visualization:<br>
Bar plots display confidence scores for digit classes.<br>
Confusion matrices for evaluating model accuracy.<br>
