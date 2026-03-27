# 🧠 Analyzing the Impact of Neural Network Depth on Learning Non-Linear Decision Boundaries

## 📌 Overview
This project investigates how the depth of a neural network affects its ability to learn complex, non-linear patterns. The study compares shallow, moderately deep, and deep neural networks using the make_moons dataset.

The goal is to demonstrate that increasing depth improves performance up to an optimal point, beyond which overfitting may occur.

---

## 🎯 Objectives
- Understand the concept of neural network depth
- Compare model performance across different depths
- Visualize decision boundaries
- Identify underfitting and overfitting behavior

---

## 📊 Dataset
The primary dataset used is the **make_moons** dataset from Scikit-learn.

- 1000 samples
- 2 features
- Binary classification
- Non-linearly separable

This makes it ideal for evaluating neural networks.

---

## 🏗️ Models Implemented

| Model | Hidden Layers | Description |
|------|-------------|------------|
| Model A | 1 Layer | Shallow (Underfitting) |
| Model B | 3 Layers | Optimal Performance |
| Model C | 5 Layers | Deep (Overfitting) |

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- NumPy

---

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/mlp-depth-analysis.git
cd mlp-depth-analysis
