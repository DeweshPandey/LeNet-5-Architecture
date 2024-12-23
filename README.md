# LeNet-5-Architecture

Implementation of the LeNet-5 architecture using PyTorch on Google Colab, designed for image classification tasks, particularly on datasets like MNIST..

# LeNet-5 Implementation in PyTorch

## 📚 Overview
This project implements the classic **LeNet-5** architecture using **PyTorch** on **Google Colab**. LeNet-5, developed by Yann LeCun, is one of the earliest Convolutional Neural Networks (CNNs) designed for **handwritten digit classification**.
This project demonstrates the implementation of LeNet-5, a pioneering Convolutional Neural Network (CNN) architecture introduced by Yann LeCun. It is specifically optimized for handwritten digit classification (e.g., MNIST dataset). The model includes two convolutional layers, two subsampling (pooling) layers, and three fully connected layers. The project is built with PyTorch and executed on Google Colab to leverage GPU acceleration for efficient training and testing.

## 🛠️ Technologies Used
- **Python**  
- **PyTorch**  
- **Google Colab**  
- **NumPy**  
- **Matplotlib**  

## 📊 Dataset
- **MNIST Handwritten Digit Dataset**  

## 📑 Model Architecture
1. **Input:** 32x32 grayscale images  
2. **Conv Layer 1:** 6 filters (5x5), Activation: tanh  
3. **Subsampling (Pooling):** Average Pooling (2x2)  
4. **Conv Layer 2:** 16 filters (5x5), Activation: tanh  
5. **Subsampling (Pooling):** Average Pooling (2x2)  
6. **Fully Connected Layers:** 120 → 84 → 10 (output classes)  
7. **Activation Function:** tanh, softmax (final layer)  

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/lenet5-pytorch.git
   cd lenet5-pytorch

