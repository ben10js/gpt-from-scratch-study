# GPT From Scratch Study

This project is a study repository implemented to understand the internal workings of the GPT architecture and the Transformer model.

## Project Description

This project implements the GPT structure from scratch using **PyTorch**, based on internet references and lectures. The primary goal is to gain a deep, "hands-on" understanding of:
- **Tensor Operations**: Managing shapes and flows of data.
- **Attention Mechanisms**: Implementing Self-Attention and Multi-Head Attention.
- **Embeddings**: Token and Positional embeddings.
- **Optimization**: Understanding the training loop, `nn.Module`, `forward` passes, and loss calculation.

## Purpose

> **Note**: This is a study project ("Study Repo").

It is designed to move beyond simple API usage and internalize the low-level details of how Large Language Models operate. It includes experiments with the architecture to verify understanding of the components.

## Tech Stack
- **Python**
- **PyTorch**

## Experiments

The model was first verified on small toy datasets to ensure that each component (tokenization, embeddings, attention, and loss) behaved as expected.  

I also ran small-scale experiments on a private Korean text corpus (personal notes).  
Because the corpus was very small, the model **failed to generate coherent sentences** and quickly overfit, but this helped me understand how data size and diversity affect training stability and sample quality.  
The private corpus is **not** included in this repository for privacy reasons.
