# 🧠 From Scratch Neural Network (SGD)

A lightweight implementation of a **fully connected neural network** built from scratch using **PyTorch tensors only** (no autograd).  
It features a manual computational graph, custom backpropagation, and batch-wise **stochastic gradient descent**.

---

## 🚀 Features
- Neural network defined and trained **without PyTorch autograd**
- Custom chain rule and matrix-based gradient computation  
- Modular structure with `edge_type_partial_gradient_block` and `compute_gradient_update_params`
- Works on **MNIST** using only forward and backward tensor operations  
- Visual loss tracking and early stopping

---

## 📓 Contents
- `training_scratch.ipynb`: Full notebook with model definition, training loop, and visualization  

---

## ⚙️ Requirements
```bash
pip install torch torchvision matplotlib tqdm
