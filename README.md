# TensorFlow Coffee Roasting Classifier

A compact TensorFlow/Keras binary-classification project using roasting **temperature** and **duration** as model inputs.

## What it demonstrates

- synthetic dataset generation with NumPy
- feature normalization with `tf.keras.layers.Normalization`
- a Keras `Sequential` neural network
- sigmoid activations
- Adam optimization
- binary cross-entropy loss
- probability thresholding for classification
- learned-weight inspection
- decision-surface visualization with matplotlib

## Model

The network uses:

- 2 input features
- 3 sigmoid hidden units
- 1 sigmoid output unit

## Data

The roasting dataset is generated directly inside the notebook, so there is no external CSV dependency.

## Run locally

```bash
pip install -r requirements.txt
jupyter notebook tensorflow_coffee_roasting.ipynb
```

## Portfolio note

This repository is a cleaned, self-contained version of work originally developed in Google Colab.
