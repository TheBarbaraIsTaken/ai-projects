# Neural Netwrok for Classification of 2D Points

## Introduction

In this project, I aim to develop a **neural network model using Keras** to analyze a dataset consisting of points with two coordinates and associated labels. The labels indicate binary classification (0 or 1) for each point representing the two sates: the point is either inside (1) or outside (0) the unit circle centered at the origin.

### Goals

My goal is to train the neural network on this data, **visualize its predictions** using a heatmap and observe the **impact of hyperparameters** on metrics, like accuracy.

I explore the training process step by step, monitoring the model's performance at each epoch and dynamically update a plot to **visualize the changes in predictions over the training**. 

Through this project, I want to gain insights into the training dynamics of neural networks and visualize their decision boundaries in a two-dimensional space.

### Research Questions

TODO:
1. How does the choice of neural network architecture affect the classification performance on 2D point data?
2. What is the impact of varying the number of neurons in the hidden layers on the model's ability to capture complex patterns in the dataset?
3. How does the learning rate influence the convergence speed and final accuracy of the neural network model during training?
4. Can different activation functions, such as ReLU, sigmoid, or tanh, lead to noticeable differences in classification accuracy for this specific dataset?
5. How does the choice of optimization algorithm (e.g., Adam, SGD) affect the training dynamics and final performance of the model?
6. What is the effect of increasing the number of training epochs on the model's ability to learn intricate decision boundaries and avoid underfitting or overfitting?
7. Can data augmentation techniques, such as rotation or scaling of the input points, improve the generalization ability of the neural network model?
8. How sensitive is the model's performance to variations in the size of the training dataset, and is there a point of diminishing returns in terms of dataset size?
9. What role does regularization (e.g., L1, L2 regularization) play in preventing overfitting of the neural network model to the training data?
10. How do different initialization methods for the model's weights (e.g., random initialization, Xavier initialization) impact the convergence speed and final performance of the model?

## Related Works


## Methodology

