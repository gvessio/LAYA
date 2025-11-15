# LAYA — Layer-wise Attention Aggregator

Minimal reference implementation of **LAYA**, an interpretable output head that assigns input-conditioned attention weights to hidden layers. This example trains a simple MLP on **Fashion-MNIST** and visualizes global and class-wise attention profiles.

## 🚀 Usage

Open and run: LAYA.ipynb

The notebook:
1. trains LAYA on Fashion-MNIST,
2. evaluates accuracy and macro-F1,
3. extracts layer-wise attention weights,
4. plots global and class-wise attention patterns.

## 🧠 What is LAYA?

LAYA aggregates all hidden representations \( h_i \) using attention scores \( \alpha_i(x) \), producing:
- depth-aware predictions,
- intrinsic, per-sample interpretability without post-hoc methods.
