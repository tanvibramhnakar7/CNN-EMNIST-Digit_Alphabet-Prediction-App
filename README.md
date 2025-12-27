# EMNIST Digit & Alphabet Classifier (Streamlit App)

A web app built with Streamlit and TensorFlow that can recognize handwritten digits (0–9), uppercase letters (A–Z), and lowercase letters (a–z) using a CNN trained on the EMNIST ByClass dataset.
You can draw directly on a digital canvas or upload an image of a handwritten character, and the app will predict which character it is along with the top 5 most likely predictions.

# Overview
This project uses a Convolutional Neural Network (CNN) trained on the EMNIST dataset to identify handwritten digits and alphabets.
It provides two easy-to-use input methods:
Draw your character on a digital canvas.
Upload an image (PNG/JPG) of a handwritten symbol.

# Model Details
Dataset: EMNIST ByClass (62 total classes)
Digits (0–9)
Uppercase letters (A–Z)
Lowercase letters (a–z)
Input shape: 28x28 grayscale images
Framework: TensorFlow/Keras
Model type: CNN (2 Conv2D + MaxPooling + Dense layers)
File: `cnn_emnist_digits_alphabets.pkl` (pickled model)

# Author
Tanvi Bramhnakar
