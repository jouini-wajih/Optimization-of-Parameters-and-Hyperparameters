# Optimization of Parameters and Hyperparameters in Supervised Learning

## Project Overview
This project investigates methods for optimizing both parameters and hyperparameters in supervised learning models. The objective is to find the best configurations that enhance the overall performance of machine learning algorithms.

## Contributors
- Fayrouz Jdai
- Wajih Jouini

## Introduction
Optimization in machine learning involves adjusting both parameters and hyperparameters to improve model performance. Parameters are learned during training, while hyperparameters are set manually and govern the training process.

## Key Concepts
- **Parameters**: Variables adjusted automatically during training (e.g., weights in a neural network).
- **Hyperparameters**: User-defined settings (e.g., learning rate, regularization terms) that influence the model's performance and training process.

## Optimization Methods
### Hyperparameter Optimization
- **Grid Search**: Systematic evaluation of all possible combinations of predefined hyperparameter values. Comprehensive but resource-intensive.
- **Random Search**: Randomly explores hyperparameter combinations. More resource-efficient but less exhaustive.
- **Bayesian Optimization**: Advanced technique that uses past evaluations to guide the search towards promising hyperparameter configurations.

### Parameter Optimization
- **Gradient Descent**: An optimization algorithm that iteratively adjusts parameters to minimize the cost function.
- **Stochastic Gradient Descent (SGD)**: A variant of gradient descent that updates parameters using random subsets of data, providing computational efficiency.
- **Momentum**: Enhances gradient descent by adding a momentum term to accelerate convergence.
- **Adam**: Adaptive Moment Estimation optimizer that combines the benefits of AdaGrad and RMSProp, adjusting learning rates based on past gradients for faster convergence.

## Key Findings
- **Heatmap Analysis**: Visualizes the impact of different `gamma` and `C` values on model accuracy. Higher values of `C` and lower values of `gamma` can result in higher test accuracy.
- **Precision Variations**: Increasing `gamma` values (with constant `C`) can lead to overfitting, highlighting the need for regularization.



## Conclusion
Effective optimization of both parameters and hyperparameters is crucial for maximizing the performance of machine learning models. The optimal approach varies with the problem at hand, emphasizing the need for thorough understanding and experimentation.

