# MLP Neural Network for Medical Image Classification Using GLCM Features

This project implements a Multilayer Perceptron (MLP) neural network to classify medical images based on features extracted using Gray-Level Co-occurrence Matrix (GLCM). 
## Why this network?

- The multilayer perceptron (MLP) neural network is one of the most common and popular neural network structures.
- It produces high-quality outputs when the internal structure is appropriately chosen.
- MLP with backpropagation has proven effective in many medical applications, such as:
  - Epidemiology
  - Predicting prostate cancer
  - Predicting unwanted pregnancy
  - Predicting death after open-heart surgery
- The fully connected architecture (input and output layers connected to the hidden layers) enables learning complex patterns.
- The sigmoid activation function allows modeling probabilities, suitable for classification tasks.

## Model Description

- **Input layer:** 59 input features (GLCM texture features extracted from images)
- **Hidden layers:** 2 layers, each with 10 neurons
- **Activation function:** Sigmoid (logistic) for hidden layers and output layer
- **Output layer:** 1 neuron producing probability of class membership
- **Training method:** Backpropagation
- **Validation:** 5-fold cross-validation to assess model performance

---

## Dependencies

- Python 3.x
- scikit-learn
- numpy

Install dependencies via pip if needed:

```bash
pip install numpy scikit-learn
