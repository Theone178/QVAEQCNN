# Quantum Adversarial Learning Framework (Q-VAE + Q-CNN)

## Overview
This project implements a hybrid quantum-classical adversarial machine learning system. The architecture integrates a Quantum Variational Autoencoder (Q-VAE) acting as a quantum encoder with a Quantum Convolutional Neural Network (Q-CNN) that serves as a feature classifier.

## Tech Stack
* **Language:** Python
* **Quantum Libraries:** Qiskit 2.2.3, Qiskit Aer
* **Machine Learning & Data:** PyTorch, NumPy, Matplotlib

## Architecture & Core Features
* **Adversarial Optimization:** Engineered a custom adversarial generation pipeline utilizing Alternating Least Squares (ALS) combined with Quantum Particle Swarm Optimization (QPSO). 
* **NISQ Noise Modeling:** The framework simulates Parameterized Quantum Circuits (PQCs) using Qiskit Aer, allowing for the accurate modeling and evaluation of Noisy Intermediate-Scale Quantum (NISQ) noise profiles.
* **Gradient Evaluation:** Leverages Parameter Shift Rules to evaluate gradient stability across the quantum circuits during backpropagation.

## Performance Results
* The integration of the ALS + QPSO adversary successfully yielded a **114% payoff boost** over the standard baseline model.

## Getting Started
1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/Quantum-Adversarial-Framework.git](https://github.com/YourUsername/Quantum-Adversarial-Framework.git)
