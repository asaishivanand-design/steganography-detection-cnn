# 🔍 Image Steganography Detection using CNN

## 📌 Project Overview
This project focuses on detecting hidden information inside digital images using Convolutional Neural Networks (CNNs). Steganography is widely used for covert communication, making its detection important in cybersecurity.

## 🚀 Motivation
With the rise of hidden data transmission techniques, detecting steganography has become a critical problem in digital forensics and cybersecurity. This project explores how deep learning can be used to identify subtle hidden patterns in images.

## 🧠 Approach
- Generated steganographic images using controlled perturbations
- Built a CNN model to classify:
  - Clean images (0)
  - Stego images (1)
- Trained on CIFAR-10 dataset

## 🏗️ Model Architecture
- Conv2D (32 filters)
- MaxPooling
- Conv2D (64 filters)
- MaxPooling
- Dense Layer (64 units)
- Dropout (0.5)
- Output Layer (Sigmoid)

## 📊 Results
- ✅ Validation Accuracy: **85.47%**
- 📉 Observed overfitting after epoch 4
- 🎯 Threshold tuning improved recall significantly

## 📈 Sample Outputs
(Add your graphs here later)
- Training vs Validation Accuracy
- Confusion Matrix

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## ▶️ How to Run
1. Clone the repository
2. https://github.com/asaishivanand-design/steganography-detection-cnn.git
3. Open Jupyter Notebook

## 📂 Project Structure

notebooks/ → Model training
results/ → Graphs
paper/ → Research paper


## 🔮 Future Improvements
- Implement real steganography (LSB, DCT)
- Use advanced datasets (BOSSBase)
- Improve CNN architecture

## 📈 Results

![Accuracy](results/accuracy.png)
![Confusion Matrix](results/confusion_matrix.png)

## 👨‍💻 Author
Appalla Sai Shivanand
