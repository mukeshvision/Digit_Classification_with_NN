# MNIST Digit Classification using Neural Network


## Project Overview

This project focuses on building a **Neural Network (NN)** model for digit recognition using the **MNIST dataset**, which is a widely used benchmark in image classification tasks. The model is trained on thousands of handwritten digits and can accurately predict digits from new unseen images. A predictive system is also integrated which allows users to input an image and get the predicted digit in real time.

---

## Dataset

- **Source:** [Keras MNIST Dataset](https://keras.io/api/datasets/mnist/)
- **Training Samples:** 60,000 images
- **Test Samples:** 10,000 images
- **Image Size:** 28x28 pixels
- **Classes:** 10 (Digits 0 to 9)

---

## Model Architecture

The Neural Network used for this classification includes:

- **Input Layer:** 784 nodes (flattened 28x28 image)
- **Hidden Layers:**
  - Dense Layer (128 units, ReLU activation)
  - Dense Layer (64 units, ReLU activation)
- **Output Layer:** 10 units (Sigmoid activation for multiclass classification)

---

## Workflow

1. **Load and Preprocess Data**
2. **Build and Compile the NN Model**
3. **Train the Model on MNIST Dataset**
4. **Evaluate on Test Set**
5. **Predict Digits from New Images**
6. **Deploy a Predictive System using `.png` image input**

---

## Prediction Example

The image below (28x28 grayscale) is passed to the trained model:

![Predicted Digit](MNIST_digit.png)

**Predicted Output:** `3`

