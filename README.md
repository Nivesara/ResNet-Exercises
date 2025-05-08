# ResNet-Exercises

# 🧠 ResNet on MNIST – Notebook Overview

This repository contains the notebook **`02_ResNet_minist.ipynb`**, where a **custom ResNet architecture** is applied to the **MNIST handwritten digits dataset** using PyTorch.

---

## 📌 Key Highlights from the Notebook

- ✅ **Custom ResNet model** built from scratch, adapted for MNIST's single-channel grayscale input
- ✅ Modified convolutional layers to handle MNIST’s 28×28 image size
- ✅ Implemented **residual blocks** to understand and leverage deep residual learning
- ✅ Complete training pipeline using the ResNet model on MNIST
- ✅ Visualized training and validation loss for performance tracking

---

## 📊 Result Summary

- 📈 The **ResNet model achieved ~98.5% test accuracy** on the MNIST dataset
- 📉 Training and validation **loss steadily decreased** across epochs
- ✅ Residual connections helped avoid vanishing gradients and improved learning stability

---

## 📉 Graph: Loss Curve

The notebook includes a plot showing:

- 🟦 **Training Loss** vs 🟥 **Validation Loss**
- A consistent drop in both curves, showing proper model convergence
- No signs of overfitting – the model generalizes well on unseen data

---
