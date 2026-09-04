# Brain Tumor Detection using Deep Learning

A deep learning-based web application for classifying brain MRI images into different brain tumor categories using **VGG16 Transfer Learning** and **Flask**.

## Project Overview

This project uses a Convolutional Neural Network based on the pretrained **VGG16** architecture to classify brain MRI images into four categories:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

The trained model is integrated with a Flask web application where a user can upload an MRI image and receive a prediction along with the model's confidence score.

## Features

- Brain MRI image classification
- Transfer learning using VGG16
- Four-class classification
- Image preprocessing and normalization
- Flask-based web interface
- MRI image upload functionality
- Prediction confidence score
- Trained model stored using Keras format

## Technologies Used

- Python
- TensorFlow
- Keras
- VGG16
- NumPy
- Scikit-learn
- Flask
- HTML
- Jupyter Notebook
- Git
- GitHub
- Git LFS

## Model Architecture

The project uses **VGG16** as the pretrained convolutional base.

The model contains:

- Input image size: `128 × 128`
- VGG16 pretrained convolutional layers
- Flatten layer
- Dropout layers
- Dense layer with 128 neurons
- Output layer for four classes
- Adam optimizer
- Learning rate: `0.0001`


## Model Performance

The trained model achieved approximately:

Training Accuracy: 97%
Test Accuracy: 95%

The test set contained approximately 1,331 MRI images.


##  Project Structure

```text
Brain-tumor-detection-project/
│
├── models/
│   └── my_model.keras
│
├── templates/
│   └── index.html
│
├── braintumordetection.ipynb
├── braintumordetection.py
├── main.py
├── .gitignore
├── .gitattributes
└── README.md

```

## Dataset

The dataset used for training contains brain MRI images divided into training and testing sets with four tumor categories.
The dataset itself is not included in this GitHub repository because of its size.


## Disclaimer

This project was created for **educational and academic purposes only**.

The predictions produced by this model should **not** be used as a substitute for professional medical diagnosis or medical advice.

## Author

**Rishita Bhowmik**

B.Sc. Data Science