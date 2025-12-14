# PSO-problem
🧠 Feature Selection using Particle Swarm Optimization (PSO)

This project demonstrates the use of Particle Swarm Optimization (PSO) for feature selection in a classification task. The goal is to identify the most relevant subset of features from a dataset to improve classification performance while reducing dimensionality.

The Breast Cancer dataset from scikit-learn is used, where only the first five features are considered. Each particle in PSO represents a binary feature mask, indicating whether a feature is selected or not.

A Decision Tree classifier is employed to evaluate each particle using classification accuracy as the fitness function. During the optimization process, particles update their velocities and positions based on:

Their personal best solution

The global best solution found so far

PSO control parameters (inertia weight, cognitive and social components)

The algorithm iteratively searches for the optimal feature subset that maximizes classification accuracy on the test set.

Key Components:

Binary Particle Swarm Optimization (BPSO)

Decision Tree classifier for fitness evaluation

Feature subset optimization

Accuracy-based objective function

This implementation provides a simple and educational example of combining metaheuristic optimization techniques with machine learning models for feature selection.
