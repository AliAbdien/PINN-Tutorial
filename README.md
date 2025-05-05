# 🔬 Physics-Informed Neural Networks (PINNs) with PyTorch

This repository demonstrates how to solve partial differential equations (PDEs) using Physics-Informed Neural Networks (PINNs), implemented in PyTorch.

## 📘 What are PINNs?

Physics-Informed Neural Networks integrate physical laws into the training of neural networks, allowing them to solve PDEs using both data and governing equations.

## 🧠 Example: Burgers' Equation

We solve the 1D nonlinear Burgers' equation:

\[
\frac{\partial u}{\partial t} + u \frac{\partial u}{\partial x} = \nu \frac{\partial^2 u}{\partial x^2}
\]

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

## 📄 License

MIT License
