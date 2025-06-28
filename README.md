# A Comparative Study of Deep Learning Optimizers: Adam, AdamW, and Adamax

## Table of Contents
- [Introduction](#introduction)
- [Motivation and Objectives](#motivation-and-objectives)
- [Overview of Optimizers](#overview-of-optimizers)
- [Implementation Details](#implementation-details)
- [Experiments and Results](#experiments-and-results)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [References](#references)

---

## Introduction
This project presents a comparative study of three popular deep learning optimizers: **Adam**, **AdamW**, and **Adamax**. The goal is to analyze their performance, convergence behavior, and suitability for different machine learning tasks.

## Motivation and Objectives
- Understand the theoretical differences between Adam, AdamW, and Adamax.
- Implement each optimizer from scratch.
- Compare their performance on benchmark datasets.
- Provide insights and recommendations for practitioners.

## Overview of Optimizers
- **Adam**: Combines the advantages of AdaGrad and RMSProp; widely used for its adaptive learning rate.
- **AdamW**: A variant of Adam that decouples weight decay from the gradient update, improving generalization.
- **Adamax**: A generalization of Adam based on the infinity norm, often more stable for certain problems.

## Implementation Details
- All optimizers are implemented in the Jupyter notebook: `Optimizers Implementation.ipynb`.
- The notebook includes code, explanations, and visualizations.
- Experiments are conducted on standard datasets (e.g., MNIST, CIFAR-10) or synthetic data for demonstration.

## Experiments and Results
- Training and validation curves are plotted for each optimizer.
- Key metrics (accuracy, loss, convergence speed) are compared.
- Observations and analysis are provided in the notebook.

## How to Run
1. Clone or download this repository.
2. Open `Optimizers Implementation.ipynb` in Jupyter Notebook or VS Code.
3. Run the cells sequentially to reproduce the results and visualizations.

## Dependencies
- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib
- (Optional) PyTorch or TensorFlow (if used for experiments)

Install dependencies using pip:
```bash
pip install numpy matplotlib jupyter
```
