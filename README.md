# steganography-detection-cnn
CNN-based detection of hidden data in images (Steganalysis)
# 🔍 Image Steganography Detection using CNN

## 📌 Overview
This project focuses on detecting hidden information inside digital images using Convolutional Neural Networks (CNNs). Steganography is often used for covert communication, making its detection important in cybersecurity.

## 🚀 What I Did
- Built a CNN model to classify images as **clean** or **stego**
- Generated steganographic images using controlled perturbations
- Trained and evaluated the model on the CIFAR-10 dataset

## 🧠 Model Architecture
- Conv2D (32 filters)
- MaxPooling
- Conv2D (64 filters)
- MaxPooling
- Dense (64 units)
- Dropout (0.5)
- Output (Sigmoid)

## 📊 Results
- Validation Accuracy: **85.47%**
- High recall achieved after threshold tuning
- Trade-off observed between precision and recall

## 📈 Key Insights
- CNNs can effectively learn hidden patterns in images
- Threshold tuning plays a critical role in detection performance
- False positives increase when sensitivity is maximized

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Matplotlib

## 📂 Project Structure
