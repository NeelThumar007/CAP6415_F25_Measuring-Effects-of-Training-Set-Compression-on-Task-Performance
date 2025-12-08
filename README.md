# CAP6415_F25_Measuring-Effects-of-Training-Set-Compression-on-Task-Performance


#Abstract

This project addresses the challenge of deploying product image classification models on mobile devices with limited storage and computational resources. The objective is to determine how much the training dataset can be compressed without significantly degrading classification accuracy. A Convolutional Neural Network (CNN) is trained on multiple dataset sizes, ranging from full data to heavily reduced subsets. Model performance is compared across compression levels using accuracy, loss, and feature-space analysis. Results show that moderate compression preserves high accuracy, enabling lightweight and efficient deployments for real-world e-commerce applications while significantly reducing memory requirements.


# Description

E-commerce Product Image Classification Under Dataset Compression

Modern e-commerce applications rely heavily on image classification models to automatically categorize products uploaded by users. However, when deploying such AI models on resource-constrained mobile devices, developers face major challenges:

Limited storage for training data

Limited computational power

Need for fast, lightweight inference

This project investigates how reducing the size of the training dataset affects the accuracy of a product image classification model. The goal is to identify the minimum amount of data required to achieve high performance, enabling mobile deployment without sacrificing usability.

A Convolutional Neural Network (CNN) is trained multiple times using different dataset compression levels. For each compressed dataset version, the model’s metrics—accuracy, loss, and feature-space consistency—are evaluated. Using these results, the project identifies an optimal compression–accuracy trade-off that allows companies to deploy efficient models while minimizing memory usage.

This approach provides practical guidance for engineers building on-device vision models for e-commerce platforms, demonstrating that smart dataset compression can dramatically reduce storage costs while maintaining strong classification performance.


