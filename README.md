---

# Lab 1: Deep Learning with PyTorch - Classification and Regression

This repository contains a comprehensive lab on using PyTorch to perform classification and regression tasks. The main goal of this lab is to establish deep learning proficiency by developing and fine-tuning Deep Neural Network (DNN) architectures to solve these tasks effectively.

---

## Objective

The primary objective is to gain practical experience in building and optimizing DNN models with PyTorch, applying them to both regression and classification datasets to understand the unique requirements of each task.

---

## Datasets

1. *NYSE Stock Dataset*: Available on Kaggle, this dataset provides historical stock prices and indicators for companies on the NYSE. It is used for regression tasks to predict continuous values such as stock prices.
   
2. *Predictive Maintenance Dataset*: Also available on Kaggle, this dataset includes sensor data used to perform multi-class classification for predictive maintenance. The goal is to categorize equipment conditions based on sensor readings.

---

## Project Workflow

### Part 1: Regression on NYSE Dataset

1. *Data Preparation*: Load and preprocess the data, including cleaning and selecting relevant features.
2. *Exploratory Data Analysis (EDA)*: Visualize and analyze trends to understand data patterns and inform model selection.
3. *DNN Architecture for Regression*: Design and implement a DNN model using PyTorch for continuous outcome prediction.
4. *Hyperparameter Tuning*: Optimize the model using GridSearchCV to find the best parameters for improved performance.
5. *Model Training and Visualization*: Plot Loss vs. Epochs and Accuracy vs. Epochs to observe model convergence and learning progress.
6. *Regularization Techniques*: Use dropout, L1, and L2 regularization to reduce overfitting, comparing results with the initial model.

### Part 2: Multi-Class Classification for Predictive Maintenance

1. *Data Preprocessing*: Clean the dataset, handle missing values, and standardize the feature scales.
2. *EDA and Data Augmentation*: Explore data distribution and apply augmentation techniques to balance classes.
3. *DNN Architecture for Classification*: Build a multi-layer DNN using PyTorch for predictive maintenance classification.
4. *Hyperparameter Tuning*: Use GridSearch for parameter optimization to enhance model performance.
5. *Evaluation and Visualization*: Analyze Loss and Accuracy plots and calculate classification metrics, such as F1-score, to assess model effectiveness.
6. *Regularization Techniques*: Add dropout and other regularization methods to improve model generalization and reduce overfitting.

---

## Results

This lab demonstrates the application of DNNs for both regression and classification, highlighting the importance of data preprocessing, hyperparameter tuning, and regularization techniques in building effective models. 

---

## Usage

1. Clone this repository:
    bash
    https://github.com/Ayoubto/Atelier1_DL.git
    
2. Install the required libraries:
   
3. Run the notebooks in your preferred environment (e.g., Google Colab, Jupyter Notebook).

---

## Synthesis

Through this lab, we gained essential experience in designing and optimizing DNNs for regression and classification tasks. Key takeaways include understanding data preparation, exploring model architectures, tuning hyperparameters, and applying regularization techniques. This project enhances skills in deep learning and demonstrates the adaptability of DNNs to various data types and tasks.

---
