# 🔬 Physics-Informed Neural Networks (PINNs) with PyTorch

This repository demonstrates how to solve partial differential equations (PDEs) using Physics-Informed Neural Networks (PINNs), implemented in PyTorch.

## 📘 What are PINNs?

Physics-Informed Neural Networks integrate physical laws into the training of neural networks, allowing them to solve PDEs using both data and governing equations.

## 🧠 Example: Burgers' Equation

We solve the 1D nonlinear Burgers' equation:

`∂u/∂t + u ∂u/∂x = ν ∂²u/∂x²`
![ChatGPT Image May 6, 2025, 12_46_11 AM](https://github.com/user-attachments/assets/a7cc7fc5-06dd-404e-a68c-5527f6800b32)


## 📂 Project Structure

```
pinn-tutorial/
│
├── notebooks/               # Jupyter notebooks
├── src/                     # Optional source code for reuse
├── README.md                # This file
├── requirements.txt         # Dependencies
└── LICENSE
```

## 🚀 How to Run

1. Install dependencies:
```
pip install -r requirements.txt
```

2. Open the Jupyter notebook:
```
cd notebooks
jupyter notebook pinn_burgers.ipynb
```

## 📈 Output

- PINN is trained to solve the Burgers' equation using physics-driven loss.
- Training loss and predicted solution are visualized.

