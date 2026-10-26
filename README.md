# Keras Functional API: Multi-Output Neural Network Tutorial

This repository contains a clean, cell-by-cell Jupyter Notebook demonstrating how to build a **non-linear neural network with multiple outputs** using the **Keras Functional API** in TensorFlow. 

Inspired by CampusX's deep learning tutorial, this project shows how to break away from traditional linear (Sequential) topologies to handle complex architectures.

---

## 🚀 What You Will Learn
* How to use the **Keras Functional API** (`tf.keras.models.Model`).
* How to pass tensors dynamically between shared hidden layers.
* How to build a **multi-output architecture** that handles both regression (predicting continuous values like Age) and binary classification (predicting categories like Gender) simultaneously.
* How to compile a model with multiple loss functions and custom loss weights.

---

## 🛠️ Requirements & Installation

Make sure you have the following libraries installed in your environment:

```bash
pip install tensorflow numpy pandas scikit-learn
