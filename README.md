# Vision Transformer (VIT) Implementation

This repository contains an implementation of the Vision Transformer (VIT) for image classification. Vision Transformers, introduced by Dosovitskiy et al. [reference] in 2020, have demonstrated remarkable performance in computer vision tasks, initially excelling in image classification and subsequently proving effective in various other tasks.

## Part 2: Vision Transformer (VIT) Tutorial

In this section, we provide a step-by-step guide to implementing a Vision Transformer from scratch using PyTorch. The tutorial covers the following steps:

1. **Architecture Setup**:

Follow the tutorial at [Vision Transformers from Scratch - PyTorch](https://medium.com/mlearning-ai/vision-transformers-from-scratch-pytorch-a-step-by-step-guide-96c3313c2e0c) to establish the VIT model architecture from scratch.

3. **Classification Task on MNIST Dataset**:

After implementing the VIT model, perform a classification task on the MNIST dataset.

5. **Results Interpretation and Comparison**:

Interpret the obtained results and compare them with the results obtained in the first part of the project.

## Code Overview

The implementation is based on PyTorch and includes the following key components:

- **MyViT Model**:

The Vision Transformer model is defined in the `MyViT` class, consisting of multiple blocks (`MyViTBlock`) and a multi-head self-attention mechanism (`MyMSA`).

- **Training and Testing**:

The `main()` function includes the training and testing pipeline, utilizing the MNIST dataset.

- **Custom Blocks and Attention Mechanism**:

Custom modules such as `MyViTBlock` and `MyMSA` are defined to build the Vision Transformer architecture.

- **Positional Embeddings and Patching**:

The code includes methods for generating positional embeddings and patchifying images.

## Usage

To run the Vision Transformer on the MNIST dataset, execute the provided code in the `main()` function. Ensure that PyTorch and other dependencies are installed. The code is designed to run on both CPU and GPU.


Feel free to experiment with different hyperparameters, architectures, or datasets to further explore the capabilities of Vision Transformers in image classification tasks.

## References:

https://medium.com/mlearning-ai/vision-transformers-from-scratch-pytorch-a-step-by-step-guide-96c3313c2e0c,
