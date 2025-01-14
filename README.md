# MLP-CNN-MedicalAnalysis
This project contains an in-depth implementation and comparison of two deep learning architectures - **Multilayer Perceptrons (MLPs)** and **Convolutional Neural Networks (CNNs)** for medical image classification using the **OrganAMNIST dataset**. The project highlights key deep learning techniques such as regularization, normalization, and architectural optimization.

## Project Overview
1. **MLPs:**
   - Built from scratch with regularization techniques to enhance sparsity and prevent overfitting.
   - Incorporated normalization strategies to stabilize training and improve convergence.
2. **CNNs:**
   - Custom convolutional layers implemented for efficient feature extraction.
   - Evaluated performance in handling complex medical image datasets.

Both architectures were tested and compared using metrics such as accuracy, loss, and inference time.

## Repository Structure
- `mlp-collab.ipynb`: Implementation of MLPs with preprocessing, training, and evaluation.
- `cnn-collab.ipynb`: Development of CNNs and performance analysis.
  
## Dataset
- **OrganAMNIST**: A subset of the MedMNIST collection, containing labeled medical images of organs. For more details, visit [MedMNIST](https://medmnist.com).

## Features
- Implementation of custom deep learning architectures from scratch.
- Regularization and normalization for improved model generalization.
- Comparative analysis to highlight the strengths and weaknesses of MLPs and CNNs.

## Technologies Used
- Python
- PyTorch
- NumPy
- Matplotlib
- OrganAMNIST Dataset
  
## Results
Key findings include:
- **MLPs:** Better suited for smaller, less complex datasets when combined with effective regularization.
- **CNNs:** Excel in feature extraction and classification of high-dimensional medical images.
