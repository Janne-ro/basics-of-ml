# Basics of ML

This repository includes self-study done on foundational machine learning concepts, including generalization, hyperparameter tuning, and cross-validation. 

**Note:** The code and explanations was done quite early in my career and does not reflect my current knowledge.

## Table of Contents
- [Project Overview](#project-overview)
- [Structure of the Repo](#structure-of-the-repo)
- [Key Features](#key-features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Project Overview

This project explores core machine learning principles through hands-on experiments and analysis. The focus is on understanding:
- The difference between training loss and generalization error
- The impact of sample size on model performance
- The use of cross-validation for model selection and hyperparameter tuning

Experiments are conducted using classic datasets and standard ML models such as linear regression, logistic regression, and support vector machines.

## Structure of the Repo

- `Trainingloss_generalization_and_crossvalidation.ipynb`: Main notebook covering training loss, generalization, and cross-validation with practical examples.
- `Different_architectures_MNIST.ipynb`: Experiments with various neural network architectures on the MNIST-1D dataset, including hyperparameter tuning and model comparison following the book [Understanding Deep Learning (UDL)]((https://udlbook.github.io/udlbook/)) by David Prince.


## Key Features

- **Learning Curves:** Visualizes how training and test errors evolve with increasing sample size.
- **Regression and Classification Tasks:** Applies linear and logistic regression to real datasets, analyzing model behavior.
- **Cross-Validation:** Demonstrates grid search for hyperparameter tuning using cross-validation.
- **Neural Network Architectures:** Compares fully connected and convolutional networks on MNIST-1D.
- **Self-Study Documentation:** All code and explanations are written from a self-study perspective.

## Setup and Installation

To run the notebooks, you will need Python and Jupyter Notebook installed.

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/basics-of-ml.git
    cd basics-of-ml
    ```
2. **(Optional) Create a virtual environment:**
    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    ```
3. **Install dependencies:**
    ```bash
    pip install numpy matplotlib scikit-learn torch
    ```

## Usage

1. **Download required datasets:** Some datasets are referenced from [LIBSVM Data](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/). Download and place them in the project directory as needed.
2. **Open a notebook:**
    ```bash
    jupyter notebook Trainingloss_generalization_and_crossvalidation.ipynb
    ```
3. **Run the cells:** Follow the explanations and execute the code cells to reproduce the experiments.

## Dependencies

- `numpy`
- `matplotlib`
- `scikit-learn`
- `torch` (for neural network experiments)