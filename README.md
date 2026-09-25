# Quantum Adversarial Learning Framework (Q-VAE + Q-CNN)

## Overview
This project implements a hybrid quantum-classical adversarial machine learning system[cite: 1, 3]. The architecture integrates a Quantum Variational Autoencoder (Q-VAE) acting as a quantum encoder with a Quantum Convolutional Neural Network (Q-CNN) that serves as a feature classifier[cite: 1, 3].

## Tech Stack
* **Language:** Python[cite: 1, 3]
* **Quantum Libraries:** Qiskit 2.2.3, Qiskit Aer[cite: 1, 3]
* **Machine Learning & Data:** PyTorch, NumPy, Matplotlib[cite: 1, 3]

## Architecture & Core Features
* **Adversarial Optimization:** Engineered a custom adversarial generation pipeline utilizing Alternating Least Squares (ALS) combined with Quantum Particle Swarm Optimization (QPSO)[cite: 1, 3]. 
* **NISQ Noise Modeling:** The framework simulates Parameterized Quantum Circuits (PQCs) using Qiskit Aer, allowing for the accurate modeling and evaluation of Noisy Intermediate-Scale Quantum (NISQ) noise profiles[cite: 1, 3].
* **Gradient Evaluation:** Leverages Parameter Shift Rules to evaluate gradient stability across the quantum circuits during backpropagation[cite: 1, 3].

## Performance Results
* The integration of the ALS + QPSO adversary successfully yielded a **114% payoff boost** over the standard baseline model[cite: 1, 3].

## Getting Started
1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/Quantum-Adversarial-Framework.git](https://github.com/YourUsername/Quantum-Adversarial-Framework.git)
