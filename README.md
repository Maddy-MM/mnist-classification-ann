# MNIST Classification using ANN

This is a beginner deep learning project where I used an Artificial Neural Network (ANN) to classify handwritten digits from the MNIST dataset.

## Project Overview
- Dataset: [MNIST dataset](http://yann.lecun.com/exdb/mnist/)
- Preprocessing: Normalized pixel values to range [0,1]
- Model: 
  - Flatten input (28x28 → 784 features)  
  - Dense layer (128 neurons, ReLU)  
  - Dense layer (32 neurons, ReLU)  
  - Output layer (10 neurons, Softmax for 10 classes)

## Training
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Metric: Accuracy
- Epochs: 25
- Validation Split: 20%

## Results
- Test accuracy: **97.5%**
- Visualized loss and accuracy during training

## Sample Prediction
The model correctly predicts handwritten digits from unseen test data.

## Learnings
- Basics of building an ANN with TensorFlow/Keras
- Preprocessing image data for neural networks
- Model training, evaluation, and visualization
