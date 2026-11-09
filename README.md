# Artificial Neural Networks: Mathematical Foundations and Optimization

> **Undergraduate Research Project — 2023**  
> **Research area:** Artificial Intelligence, Neural Networks and Optimization  
> **Research group:** LaSIA — Laboratory of Intelligent Systems and Automation  
> **Author:** Sarah Modesto Sanches and Angela Marim Bosetti

---

## Overview

This repository contains the work developed during my first undergraduate research project in **2023**, focused on studying the mathematical foundations of **Artificial Neural Networks (ANNs)** and understanding the optimization procedures behind their training.

The project was primarily theoretical and computational. Rather than treating neural networks as black-box models, the objective was to understand the mathematical mechanisms that allow a network to learn from data.

The study covered the formulation of neural networks, error functions, gradient-based optimization and different optimization algorithms. As part of the learning process, a neural network was also implemented **from scratch**, allowing the training process to be studied directly from its mathematical formulation.

This project established the foundations for the subsequent research projects involving neural networks and machine learning applications.

---

## Research Context

The initial research question was essentially:

> **How does an artificial neural network learn, and how can its mathematical formulation be implemented computationally?**

To answer this question, the work progressed from the mathematical representation of a neural network to the numerical optimization methods used to adjust its parameters.

The main concepts studied were:

- artificial neurons;
- neural network architectures;
- activation functions;
- forward propagation;
- loss functions;
- error minimization;
- gradients;
- backpropagation;
- numerical optimization;
- iterative parameter updating.

This progression was important for developing a solid understanding of what occurs internally during neural network training.

<img width="1006" height="471" alt="image" src="https://github.com/user-attachments/assets/aa320646-2e15-4adc-b673-4ebcf1284b6c" />

---

## Main Objectives

### General objective

To study the mathematical and computational foundations of artificial neural networks, with emphasis on the optimization procedures used during training.

### Specific objectives

- Understand the mathematical representation of artificial neural networks;
- Study how network parameters are optimized during training;
- Understand the role of gradient-based optimization;
- Study different optimization algorithms;
- Implement the training process computationally;
- Develop a neural network without relying entirely on high-level machine-learning frameworks;
- Compare the conceptual differences between optimization strategies.

---

## Optimization Methods

Several optimization approaches were studied during the project.

### Gradient Descent

Gradient descent was studied as the fundamental mechanism for iterative minimization of a loss function.

The general update rule can be represented as:

\[
\theta_{k+1}
=
\theta_k
-
\eta \nabla J(\theta_k)
\]

where:

- \(\theta\) represents the model parameters;
- \(J(\theta)\) is the objective function;
- \(\nabla J(\theta)\) is its gradient;
- \(\eta\) is the learning rate.

The method provided the mathematical foundation for understanding how neural network parameters can progressively move toward regions of lower error.

---

### Levenberg–Marquardt

The **Levenberg–Marquardt (LM)** algorithm was studied as another optimization strategy, particularly relevant to nonlinear least-squares problems.

The method combines characteristics of gradient-descent approaches and second-order optimization, making it particularly interesting for neural-network training and nonlinear regression problems.

Studying LM alongside gradient descent and Adam helped broaden the understanding of how different optimization strategies approach the same fundamental problem:

> **minimizing the network's prediction error by adjusting its parameters.**

---

## Neural Network Implementation from Scratch

One of the main practical activities of the project was the implementation of a neural network without treating a high-level neural-network library as a black box.

The implementation was used as a way of connecting the mathematical concepts studied throughout the project with an executable computational model.

The training process can be summarized as:

```text
Input data
    ↓
Forward propagation
    ↓
Network prediction
    ↓
Loss calculation
    ↓
Gradient calculation
    ↓
Parameter update
    ↓
New prediction
    ↓
Repeat
```

This approach made it possible to investigate the individual steps involved in neural-network learning and understand how the optimization algorithm affects the evolution of the model.

---

## From Mathematics to Code

A central aspect of this project was connecting the theoretical formulation with its computational implementation.

The workflow followed the general structure:

```text
Mathematical formulation
        ↓
Neural network model
        ↓
Loss function
        ↓
Optimization method
        ↓
Parameter update
        ↓
Iterative training
        ↓
Model evaluation
```

This transition from mathematical equations to executable code became an important foundation for the machine-learning research developed in the following years.

---

## Main Skills Developed

The project contributed to the development of skills in:

- Mathematical modeling;
- Artificial neural networks;
- Numerical optimization;
- Gradient-based methods;
- Algorithm implementation;
- Python programming;
- Scientific computing;
- Computational experimentation;
- Interpretation of machine-learning training processes.

More importantly, it established a conceptual understanding of **why neural networks work**, rather than only how to use existing machine-learning libraries.

---

## Research Contribution

Although this first project was primarily focused on foundations, it established the methodological basis for the research developed in subsequent years.

The progression can be summarized as:

```text
2023
Mathematical foundations
        ↓
Neural network optimization
        ↓
2024
Machine learning applied to scientific data
        ↓
2024–2025
Machine learning with limited datasets
        ↓
2025
Virtual sample generation and dynamic systems
        ↓
2025–2026
Recurrent neural networks for dynamic systems
        ↓
2026
Physics-informed RNNs for mobile robot localization
```

Thus, the 2023 project represents the starting point of a research trajectory that progressively moved from **fundamental neural-network theory to scientific and robotic applications**.

---

## Technologies and Tools

The project involved computational implementation and experimentation using tools for scientific programming and machine-learning development.

**Main topics/tools:**

- Python
- Numerical computing
- Artificial Neural Networks
- Optimization algorithms
- Gradient-based learning
- Scientific programming

---

## Repository Contents

The repository contains the computational materials developed during the research project, including implementations and experiments related to neural networks and optimization.

The code is preserved as part of the research history and documents the transition from theoretical study to practical implementation.

---

## Research Evolution

This project was the starting point for the subsequent development of my research in machine learning.

The main evolution was:

### 2023 — Foundations

**Understanding neural networks and optimization**

↓

### 2024 — Application

**MLP models applied to environmental and chemical data**

↓

### 2024–2025 — Limited Data

**Investigation of machine learning with small datasets**

↓

### 2025 — Virtual Data and Dynamic Systems

**GPR-based virtual sample generation and neural networks for dynamic systems**

↓

### 2025–2026 — Mobile Robotics

**Recurrent neural networks applied to DDMR dynamics**

↓

### 2026 — Physics-Informed RNNs

**Pose estimation of differential-drive mobile robots**



### Related Research

This repository is part of a sequence of research projects developed between **2023 and 2026**, progressively moving from the foundations of artificial neural networks toward their application to scientific data, limited-data problems and mobile robotics.
