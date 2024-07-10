# Predicting Airline Passenger Satisfaction using Multilayer Perptron (MLP) and  Support Vector Machine (SVM)

## Project Overview

This project aims to evaluate, compare, and contrast two machine learning models: Support Vector Machine (SVM) and Multilayer Perceptron (MLP), for predicting airline passenger satisfaction. We focus on a binary classification task where we predict whether passengers are 'Satisfied' or 'Neutral or dissatisfied' based on various attributes. The best-performing models are identified through hyperparameter tuning using grid search with 10-fold cross-validation. Our evaluation involves comparing several performance metrics to determine the strengths and weaknesses of each model.

## Objectives

The aim of this project is to critically evaluate two algorithm models, the SVM and the MLP, for a binary classification task of predicting the satisfaction of airline passengers. The task involves predicting whether a person is classified as ‘Satisfied’ or ‘Neutral or dissatisfied’ based on a set of attributes. Through this analysis, we assess the effectiveness of MLP and SVM models in predicting passenger satisfaction within the airline industry. By identifying their strengths and weaknesses, we provide insights to guide airline management decisions, ultimately enhancing management practices.

## Key Findings

- SVM generally outperformed MLP in various metrics but showed signs of overfitting with higher train accuracy compared to test accuracy.
- MLP demonstrated better generalisation capabilities and faster testing time efficiency despite slightly lower performance metrics.
- The project emphasized the importance of balancing model complexity with performance metrics.
- Overfitting concerns with SVM due to its complex non-linear kernel decision boundary.
- Future research could explore regularisation techniques or reduce SVM model complexity to mitigate overfitting.

## Repository Contents
- `Entire code.ipynb`: Jupyter Notebook containing the entire code for the project.
- `MLP model.ipynb`: Jupyter Notebook for the MLP model.
- `SVM model.ipynb`: Jupyter Notebook for the SVM model.
- `Paper.pdf`: PDF report of the project.
- `best_mlp.pkl`: Pre-trained best MLP model.
- `best_mlp.pkl`: Pre-trained best SVM model.
- `readme.txt`: Additional instructions.
- `test_dataset.csv`: Preprocessed test dataset.

## Getting the Dataset
Please download the dataset from [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction) and place it in the Data directory before running the notebooks.

## Conclusion

This project demonstrates the application of SVM and MLP models for predicting airline passenger satisfaction. The findings provide insights into their strengths and weaknesses, offering guidance for airline management decisions to enhance service quality and passenger satisfaction.
