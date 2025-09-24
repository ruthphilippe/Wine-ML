🍷 Wine Classification with Neural Networks

This project trains a simple neural network using TensorFlow/Keras on the Wine dataset
 (available in sklearn.datasets).
The goal is to classify wine samples into 3 categories based on 13 chemical features.

📌 Project Overview

Dataset: Wine dataset (178 samples, 13 features, 3 classes)

Framework: TensorFlow / Keras

Task: Multi-class classification

Metric: Accuracy

⚙️ Requirements

Install dependencies:

pip install tensorflow scikit-learn matplotlib

🧠 Model Architecture

Input layer: 13 features

Hidden layer 1: 32 units, ReLU

Hidden layer 2: 16 units, ReLU

Output layer: 3 units, Softmax

📊 Results

Achieved ~94% test accuracy.

Training and validation loss decreased smoothly without overfitting.

Accuracy plot shows steady improvement over epochs.

Training Curves

Accuracy: Train ~0.90, Validation ~0.85–0.88

Loss: Both train & validation decrease steadily
