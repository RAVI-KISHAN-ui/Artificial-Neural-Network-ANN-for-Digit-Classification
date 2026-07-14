# Handwritten Digit Classification using Artificial Neural Network (ANN)

 Project Overview
 
This project implements an Artificial Neural Network (ANN) to classify handwritten digits using the MNIST dataset. The model is built using TensorFlow and Keras. It is trained on the MNIST dataset and evaluated using accuracy and loss metrics.

Objective

- Build an Artificial Neural Network (ANN) for digit classification.
- Train the model on the MNIST dataset.
- Evaluate the model using accuracy and loss.
- Predict handwritten digits from the test dataset.

 Dataset
 
Dataset Name: MNIST

- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10 (Digits 0–9)

Dataset Link:
https://keras.io/api/datasets/mnist/

 Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

Model Architecture

Input (28 × 28)

↓

Flatten Layer

↓

Dense (128, ReLU)

↓

Dense (64, ReLU)

↓

Dense (10, Softmax)

 Training Details

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Activation Function: ReLU
- Output Activation: Softmax
- Epochs: 10
- Validation Split: 20%

 Evaluation Metrics

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Training Loss
- Validation Loss

 Results

The ANN model successfully classified handwritten digits with high accuracy. The training and validation accuracy improved over epochs, while the loss decreased, indicating effective learning.

Project Structure

```
Assignment_1_ANN/
│
├── ANN_MNIST.ipynb
├── README.md
├── Report.pdf
└── images/
    ├── dataset.png
    ├── model_summary.png
    ├── accuracy.png
    ├── loss.png
    └── predictions.png
```

 How to Run

1. Open the Jupyter Notebook or Kaggle Notebook.
2. Install the required libraries:
   ```bash
   pip install tensorflow matplotlib numpy
