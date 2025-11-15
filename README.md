# 🧠 Handwritten Digit Recognition — Deep Learning Practice Task

This repository contains a simple Deep Learning practice task using the **MNIST dataset**.  
The goal is to recognize handwritten digits (0–9) using a basic **Artificial Neural Network (ANN/DNN)** built with Keras.

---

## 📌 Task Overview

In this practice task, the following steps were performed:

- Loaded the MNIST dataset using Keras  
- Applied basic data preprocessing (reshaping + normalization)  
- Built a simple ANN/DNN model with:
  - `Dense(512, ReLU)`
  - `Dense(64, ReLU)`
  - `Dense(10, Softmax)`
- Trained the model for 20 epochs  
- Achieved **98%+ accuracy** on test data  
- Saved the trained model as:


- Loaded the model in another file to verify predictions  
- Successfully tested multiple predictions ✔

---

## 🏗️ Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- MNIST Dataset  

---

## 📈 Model Accuracy

**Final Test Accuracy: ~98%**

---

## 🗂️ Files Included

- `train_model.py` — Model training + saving  
- `load_model.py` — Load model + prediction testing  
- `HandDigitRecognition.h5` — Saved trained model  

---

## 🎯 Purpose

This practice task helped enhance understanding of:

- Building neural networks  
- Training & evaluating models  
- Saving and reloading models for future use  

---

## 🤝 Contributions

This is a learning-oriented repository.  
Suggestions and improvements are always welcome!

---
