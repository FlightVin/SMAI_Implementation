# SMAI_Implementation

This repository contains a series of comprehensive implementations of statistical modeling and machine learning algorithms, developed as part of a course on **Statistical Methods in AI**. The project showcases a deep understanding of core machine learning concepts, with a focus on building models from the ground up, optimizing their performance, and exploring the theoretical foundations behind these techniques.

For brevity, data sources have not been included. Each part of the project includes extensive hyperparameter tuning, data exploration, and model optimizations wherever possible, emphasizing the importance of performance efficiency and practical applicability.

## Table of Contents

1. [Part 1: k-Nearest Neighbours and Decision Trees](#part-1-k-nearest-neighbours-and-decision-trees)
2. [Part 2: PCA, Gaussian Mixture Models, and Clustering](#part-2-pca-gaussian-mixture-models-and-clustering)
3. [Part 3: Linear Models, MLPs, CNNs, and Autoencoders](#part-3-linear-models-mlps-cnns-and-autoencoders)
4. [Part 4: Ensemble Methods](#part-4-ensemble-methods)
5. [Part 5: Kernel Density Estimation and Hidden Markov Models](#part-5-kernel-density-estimation-and-hidden-markov-models)

## Part 1: k-Nearest Neighbours and Decision Trees

- **k-Nearest Neighbours (k-NN)**: Implemented the k-NN algorithm from scratch, focusing on optimizing the algorithm through vectorization techniques to enhance computational efficiency. This implementation lays the foundation for understanding the role of distance metrics in classification tasks and the importance of algorithm optimization.
  
- **Decision Trees**: Explored the powerset and multi-output formulations of classification using decision trees. These advanced techniques demonstrate the flexibility of decision trees in handling complex classification problems with multiple outputs, providing insights into the interpretability and structure of tree-based models.

## Part 2: PCA, Gaussian Mixture Models, and Clustering

- **Principal Component Analysis (PCA)**: Implemented PCA from scratch, emphasizing its role in dimensionality reduction and feature extraction. This implementation highlights the importance of understanding variance and feature correlation in high-dimensional datasets.
  
- **Gaussian Mixture Models (GMMs)**: Developed the Expectation-Maximization algorithm for GMMs from the ground up. This project section underscores the significance of probabilistic modeling in clustering tasks and the application of GMMs in scenarios where data may belong to multiple distributions.
  
- **Hierarchical Clustering**: Conducted ablation studies on hierarchical clustering, providing insights into the clustering process and its sensitivity to different linkage criteria and distance metrics. This work emphasizes the importance of cluster structure and dendrogram analysis in unsupervised learning.

## Part 3: Linear Models, MLPs, CNNs, and Autoencoders

- **Multinomial Linear and Logistic Regression**: Implemented these foundational models from scratch, focusing on their application to multi-class classification problems. These implementations reinforce the importance of understanding gradient-based optimization and the decision boundaries in classification tasks.
  
- **Multilayer Perceptrons (MLPs)**: Built MLPs from the ground up, exploring the role of hidden layers and activation functions in deep learning. This section illustrates the power of neural networks in approximating complex functions and the challenges of training deep architectures.
  
- **Convolutional Neural Networks (CNNs) and Autoencoders**: Leveraged inbuilt Torch modules to implement CNNs and autoencoders, focusing on their application to image processing tasks. This work highlights the importance of convolutional operations in feature extraction and the role of autoencoders in unsupervised learning and dimensionality reduction.

## Part 4: Ensemble Methods

- **Bagging and Stacking**: Implemented Bagging and Stacking algorithms from scratch, demonstrating the power of ensemble learning in reducing variance and improving predictive performance. This section showcases the importance of combining multiple models to achieve better generalization.

- **Random Forest, AdaBoost, and Gradient Boosted Decision Trees**: Developed these powerful ensemble methods, emphasizing their application to a variety of machine learning tasks. These implementations highlight the trade-offs between bias and variance and the effectiveness of boosting techniques in creating strong learners from weak ones.

## Part 5: Kernel Density Estimation and Hidden Markov Models

- **Kernel Density Estimation (KDE)**: Implemented KDE from scratch, providing a non-parametric approach to estimating probability densities. This work emphasizes the importance of bandwidth selection and kernel functions in accurately modeling data distributions.
  
- **Hidden Markov Models (HMMs)**: Tuned HMM parameters for diverse applications, exploring their role in sequence modeling and time series analysis. This section highlights the significance of probabilistic graphical models in capturing temporal dependencies and latent structures in data.
