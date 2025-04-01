# 🌈 CIFAR-10 CNN Classifier 📊

A convolutional neural network implementation for classifying CIFAR-10 images using PyTorch.

## ✨ Performance
**84% accuracy** on the CIFAR-10 test set! 🎯
This model successfully identifies common objects with high precision.

## 🏗️ Model Architecture
This project uses a deep CNN with 5 convolutional blocks followed by a fully connected classifier:
- **5 Convolutional Blocks**: Each with Conv2D → BatchNorm → ReLU → MaxPool
- **Classifier**: 2-layer fully connected network (1024 → 1024 → output classes)

## 🛠️ Requirements
- torch>=1.7.0
- torchvision>=0.8.1
- numpy
- matplotlib

## 📊 Dataset
The [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset consists of 50,000 training and 10,000 test color images (32x32) of 10 object categories:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck
