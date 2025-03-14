# **HandWritten Digit Recognition**

## Overview
This project implements a neural network to classify handwritten digits from the MNIST dataset.  
It uses TensorFlow and Keras to train a Multi-Layer Perceptron (MLP) model, achieving high accuracy.

## Background
This is a machine learning project inspired by Andrew Ng’s Machine Learning course.  
It applies fundamental deep learning concepts to classify handwritten digits.

### Libraries Used:
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib 
## Model Implementation
The model is a feedforward neural network with:
- Input Layer: Flattened 28x28 pixel images.
- Two Hidden Layers: 300 and 100 neurons with ReLU activation.
- Output Layer: 10 neurons with Softmax activation.

## Training and Performance
The model is trained for **15 epochs** using **Stochastic Gradient Descent (SGD)** and `sparse_categorical_crossentropy` loss function.  
### Test Accuracy:
After training, the model achieved **98%** accuracy on the test set.

