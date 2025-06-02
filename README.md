# Steel Surface Defect Detection with CNN

This project applies deep learning techniques to automatically detect surface defects in steel using image classification. A Convolutional Neural Network (CNN) is trained to identify and classify defects in grayscale steel images, based on a labeled dataset.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Mp-3adel/Steel_Defact_Detaction/blob/main/Steel_Defact_Detaction.ipynb)

## 🚀 Project Overview

Detecting defects in steel surfaces is critical in the quality control pipeline of steel production. This project uses a custom CNN built with TensorFlow/Keras to identify whether a steel image contains a defect. The model is trained on a labeled dataset of steel surface images and evaluated using accuracy and loss metrics.

## 🧠 Features

- Custom CNN for binary image classification
- Image preprocessing using OpenCV and NumPy
- Data loading from Google Drive
- Accuracy/loss visualization
- Google Colab-compatible

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib
- Google Colab

## 📊 Dataset

The dataset used includes grayscale images of steel with and without defects. Images are loaded from Google Drive, and preprocessed for CNN input.

> Note: Ensure the dataset is properly mounted in Google Drive before running.

## 🧪 Model Summary

- CNN architecture: Convolutional layers → MaxPooling → Dense layers
- Optimizer: Adam
- Loss function: Binary Crossentropy
- Metric: Accuracy

## 📈 Results

- Training accuracy: ~98%
- Validation accuracy: ~96%
- Successfully distinguishes between defective and non-defective surfaces

## ▶️ How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com).
2. Mount your Google Drive to access dataset.
3. Run the cells step by step to train and test the model.

## 📬 Contact

For feedback or collaboration, feel free to reach out:  
📧 [your.email@example.com](mailto:ps.mohamed.adel@gmail.com)  


---

