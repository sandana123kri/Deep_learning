# Deep Learning Implementations

This repository contains two separate implementations of deep learning models using dense neural networks. These models demonstrate the use of dense layers for different supervised learning tasks: classification and regression.

## 1. **Classification Model (MNIST Dataset)**

The first implementation is a classification model trained on the MNIST dataset. This dataset consists of 28x28 grayscale images of handwritten digits (0-9). The model uses a fully connected neural network (dense layers) to classify the images into one of the 10 possible digit classes. 

### Key Features:
- **Dataset**: MNIST (60,000 training images and 10,000 test images)
- **Model**: Fully connected neural network with multiple dense layers
- **Activation**: ReLU activation for hidden layers and softmax activation for the output layer
- **Loss Function**: Categorical cross-entropy
- **Optimizer**: Adam optimizer

## 2. **Regression Model (Toyota Corolla Dataset)**

The second implementation is a regression model designed to predict car prices based on features from the Toyota Corolla dataset. This dataset includes various attributes such as car age, mileage, fuel type, and others. The model uses dense layers to predict the continuous target variable, which is the price of the car.

### Key Features:
- **Dataset**: Toyota Corolla (used car dataset with 1,440 examples)
- **Model**: Fully connected neural network with multiple dense layers
- **Activation**: ReLU activation for hidden layers and linear activation for the output layer
- **Loss Function**: Mean Squared Error (MSE)
- **Optimizer**: Adam optimizer

## Setup

To run the models, clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-repo/deep-learning-implementations.git
cd deep-learning-implementations
pip install -r requirements.txt
```

## Usage

Once the dependencies are installed, you can run the models using the provided scripts for classification or regression tasks.

---
