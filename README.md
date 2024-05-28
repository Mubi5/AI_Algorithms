# AI_Algorithms
**Project Overview**
This repository contains implementations of two machine learning algorithms: Decision Tree and Deep Feedforward Multilayer Perceptron (MLP). Both algorithms are trained using three different types of datasets: text, numeric, and images. The purpose of this project is to demonstrate the versatility and performance of these algorithms across various data types.

**Repository Structure**
├── datasets
│   ├── text
│   ├── numeric
│   └── images
├── models
│   ├── decision_tree
│   └── deep_feedforward_mlp
├── notebooks
│   ├── decision_tree_text.ipynb
│   ├── decision_tree_numeric.ipynb
│   ├── decision_tree_images.ipynb
│   ├── deep_feedforward_mlp_text.ipynb
│   ├── deep_feedforward_mlp_numeric.ipynb
│   ├── deep_feedforward_mlp_images.ipynb
│   
├── README.md

**Algorithms**
**1. Decision Tree**
The Decision Tree algorithm is a non-parametric supervised learning method used for classification and regression tasks. It works by recursively partitioning the data space and fitting a simple prediction model within each partition.

**2. Deep Feedforward Multilayer Perceptron (MLP)**
The Deep Feedforward MLP is a class of neural network models that consist of multiple layers of nodes. Each layer is fully connected to the next one, and the network is trained to minimize the prediction error using backpropagation.

**Datasets**
**1. Text Data**
The text dataset includes samples of textual information that are processed and transformed into numerical representations (e.g., TF-IDF, word embeddings) suitable for input into the algorithms.

**2. Numeric Data**
The numeric dataset consists of purely numerical features that can be directly fed into the algorithms for training and evaluation.

**3. Image Data**
The image dataset includes visual data that are preprocessed (e.g., resized, normalized) before being used to train the algorithms. For the MLP, images are flattened into 1D vectors.

**Running the Notebooks**
Each notebook in the notebooks directory corresponds to a specific combination of algorithm and dataset type. You can run these notebooks to train and evaluate the models.

**Example**
To run the Decision Tree on text data, open and execute the cells in decision_tree_text.ipynb.

**Common Utilities**
The common_utils.ipynb notebook contains helper functions and utilities that are shared across different notebooks, such as data loading, preprocessing, and evaluation metrics.

**Results**
Each notebook includes the training and evaluation results for the respective algorithm and dataset type. Comparisons and performance metrics are provided to highlight the strengths and weaknesses of each approach.

**Contributions**
Contributions to this project are welcome. If you have any improvements, suggestions, or bug fixes, please create a pull request or raise an issue.
