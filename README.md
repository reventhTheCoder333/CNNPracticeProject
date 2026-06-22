CNN-based Fashion Image Classification
This project marks my first foray into building a Convolutional Neural Network (CNN). Using the Fashion-MNIST dataset, I designed and trained a custom deep learning model to classify clothing items, utilizing PyTorch and GPU acceleration for efficient training.

Project Overview
The objective of this project was to understand the fundamental building blocks of a CNN. The workflow follows a standard image classification pipeline:

Data Loading: Utilizing torchvision.datasets.FashionMNIST.

Preprocessing: Transforming raw images into tensors.

Model Architecture: Creating a multi-layer network with:

Convolutional Layers for feature extraction.

ReLU Activation for non-linearity.

Max Pooling to reduce spatial dimensions.

Flatten & Linear Layers for final classification.

Training: Implementing a training and testing loop to optimize model performance over 3 epochs.

Key Technologies
Python

PyTorch (torch, torchvision, nn)

Google Colab (for GPU-accelerated training)

Matplotlib (for data visualization)

Results
The model successfully converged over 3 epochs, achieving:

Final Training Loss: ~0.26

Final Test Loss: ~0.30

Device Used: NVIDIA T4 GPU (via CUDA)

Lessons Learned
Through this project, I gained practical experience in:

Managing device-agnostic code (cuda vs cpu).

Understanding how to maintain spatial hierarchies in images using Conv2d layers.

Debugging common PyTorch issues like shape mismatches between layers.

How to Run
Clone this repository to your local machine or open the .ipynb file directly in Google Colab.

Ensure you have the required libraries installed:

Bash
pip install torch torchvision tqdm matplotlib pandas
Execute the cells sequentially to observe the training process and loss metri
