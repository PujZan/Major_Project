A Federated Learning-Based Deep Learning Model for Multiclass Lung Image Classification

This project leverages federated learning to implement a privacy-preserving, decentralized deep learning model for the multiclass classification of lung images. Using ResNet-101 as the backbone, the model classifies medical images into categories such as COVID-19, pneumonia hernia, infiltration, cardiomegaly and other lung conditions having total of 15 different classes, while ensuring that sensitive medical data remains distributed across multiple devices or institutions.

Key Features: Federated Learning Framework: Enables decentralized training, where data stays on local devices, ensuring privacy.

ResNet-101 Architecture: Pretrained on ImageNet and fine-tuned for the lung image classification task, ensuring high accuracy.

Loss Function: Utilizes CrossEntropyLoss with class weights to handle class imbalance effectively.

Input Data: Processes RGB lung images with data augmentation to improve generalization and prevent overfitting.

Performance Metrics: Evaluates the model using accuracy, precision, recall, and F1-score, specifically tailored for multiclass classification tasks.

Optimization Strategies: Implements federated optimization techniques, learning rate scheduling, and weight decay, dropout for efficient and robust training.

Objectives: The primary goal of this project is to develop a privacy-preserving and collaborative solution for lung condition detection using medical imaging. By utilizing federated learning, institutions can collaboratively train a robust model without sharing sensitive patient data, promoting data security and accessibility.
