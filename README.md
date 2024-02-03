# Cat and Dog Classification using SVM Model

This repository contains an implementation of a Support Vector Machine (SVM) for the classification of images as either cats or dogs. The model is trained on the Kaggle dataset, a popular collection of cat and dog images, to demonstrate the capabilities of SVM in image classification tasks.

## Problem Statement

The objective of this project is to develop a robust image classification model using a Support Vector Machine. The model will be trained to differentiate between images of cats and dogs. This task is a classic binary classification problem in computer vision, and the SVM algorithm is chosen for its effectiveness in handling high-dimensional data and non-linear decision boundaries.

## Dataset

The dataset used for training and evaluating the model is sourced from Kaggle: [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data). It consists of a large number of labeled images of cats and dogs, providing a diverse set of data for training the SVM model.

## Result

|           | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Class 0   |   0.67    |  0.62  |   0.64   |  1011   |
| Class 1   |   0.64    |  0.68  |   0.66   |   989   |
| Accuracy  |           |        |   0.65   |  2000   |
| Macro Avg |   0.65    |  0.65  |   0.65   |  2000   |
| Weighted Avg |  0.65 |  0.65  |   0.65   |  2000   |
