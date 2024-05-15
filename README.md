# Decision Tree
This repository hosts a Python script designed to build a decision tree classifier from scratch. It explores fundamental operations required to construct a decision tree, such as calculating entropy, information gain, and performing data splits. The script also incorporates visualization tools that assist in understanding the structure of the tree.

## Installation Instructions:
- ***Ensure Python and the following libraries are installed***: pandas, numpy, matplotlib.pyplot.
- ***Install Graphviz*** for tree visualization and configure your system path to include the Graphviz directory.

## Imports and Setup
The script starts by importing necessary Python libraries and adjusting the system path to include directories for additional utility functions.

## Data Initialization
Initializes X_train and y_train arrays with features and labels respectively, using binary encoding to represent the presence or absence of certain characteristics.
## Utility Functions
- ***entropy(p)***: Computes the entropy of a binary distribution.
- ***split_indices(X, index_feature)***: Divides indices based on the value of a specified feature.
- ***weighted_entropy(X, y, left_indices, right_indices)***: Calculates the entropy of two subsets after a data split.
- ***information_gain(...)***: Calculates the information gain from a data split.

## Evaluating Splits
The script evaluates each feature's effectiveness as a decision node by calculating its information gain.

## Building and Visualizing the Decision Tree
Constructs the decision tree recursively and visualizes it using Graphviz integration, allowing for visual representations of the tree structure.

## Graphviz Integration
Details the setup required for Graphviz, critical for rendering the tree diagrams.

## Summary:
This script serves as a comprehensive guide to understanding decision trees, integrating both theoretical concepts and practical implementations. It is a valuable educational resource for learners looking to delve into machine learning algorithms, particularly in optimizing decision tree classifiers.
