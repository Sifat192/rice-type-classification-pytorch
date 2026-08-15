# Rice Type Classification Using PyTorch

A deep learning project that uses **PyTorch** to classify rice types based on morphological features of rice grains.

## 📌 Project Overview

This project implements a complete PyTorch-based deep learning workflow for a rice type classification task.

The model learns from numerical morphological characteristics of rice grains and predicts the corresponding rice type. The project focuses on understanding the fundamental components of a PyTorch training pipeline, including dataset preparation, data loading, neural network construction, training, and evaluation.

## 🎯 Objective

The main objective is to build and train a neural network using **PyTorch** for rice type classification and gain practical experience with the core components of a deep learning workflow.

## 📊 Dataset

The project uses the **Rice Type Classification Dataset**, which contains morphological measurements extracted from rice grains.

The features include measurements such as:

- Area
- Major Axis Length
- Minor Axis Length
- Eccentricity
- Convex Area
- EquivDiameter
- Extent
- Perimeter
- Roundness
- Aspect Ratio

The target variable represents the rice type/class.

## 🧠 Model

A neural network is implemented using **PyTorch**.

The project includes:

- Custom dataset preparation
- PyTorch `Dataset`
- PyTorch `DataLoader`
- Feature preprocessing
- Neural network implementation
- Forward propagation
- Loss calculation
- Backpropagation
- Model optimization
- Test-set evaluation

## ⚙️ Workflow

```text
Rice Dataset
     ↓
Data Preprocessing
     ↓
Train/Test Split
     ↓
PyTorch Dataset
     ↓
DataLoader
     ↓
Neural Network
     ↓
Training
     ↓
Model Evaluation
     ↓
Rice Type Prediction
