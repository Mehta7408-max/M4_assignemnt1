# Assignment: SGD and Attention Contextualization

## Overview
This repository contains the implementation and explanation of two fundamental concepts in machine learning and deep learning:

*Part A: Stochastic Gradient Descent (SGD)
*Part B: Self-Attention and Contextualized Word Representations

The assignment focuses on understanding how models learn from data and how context influences word representations.
# Part A: Stochastic Gradient Descent (SGD)
# Description
In this part, a simple linear regression model is trained using **Stochastic Gradient Descent** on a small subset of the Swedish Auto Insurance dataset.

# Key Concepts Demonstrated
- Incremental learning using SGD
- Weight updates after each data sample
- Role of loss function and gradients
- Effect of learning rate on parameter updates

### Dataset
- Swedish Auto Insurance Dataset
- First 3 samples are used for demonstration

# Part B: Attention Contextualization
# Description
This part demonstrates how **self-attention** creates context-aware word representations, unlike static embeddings.

A homonym ("bat") is used in two different contexts:
- Sports context: *hit ball bat*
- Animal context: *bat flew cave*

# Key Concepts Demonstrated
- Static vs contextual word embeddings
- Self-attention using Q = K = V
- Attention weight visualization using heatmaps
- Contextual shift validation using cosine similarity

# Files in This Repository
-  Main notebook containing code, outputs, and visualizations
- `README.md`–Assignment overview and explanation

# Results and Observations
- SGD updates model parameters step by step based on error gradients
- Self-attention modifies word representations based on surrounding context
- The same word can have different vector representations depending on usage
  
# Conclusion
This assignment provides a conceptual understanding of:
- How models learn using gradient-based optimization
- How attention mechanisms enable context-aware representations
   
These ideas form the foundation of modern machine learning and Transformer-based models.
