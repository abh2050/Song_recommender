# Song Recommender from Audio Data

![Project Image Record]([https://assets.datacamp.com/production/project_449/img/iphone_music.jpg](https://pbs.twimg.com/media/Ec-AKerUcAAdwbW.jpg))

## Introduction

This Colab notebook explores the task of building a song recommender system based on audio data analysis. The goal is to classify songs into either 'Hip-Hop' or 'Rock' genres without listening to them. This recommendation system relies on analyzing audio features and applying machine learning algorithms.

## Table of Contents

1. **Preparing our dataset**
    - Introduction to the dataset and its components.
    - Loading metadata and track metrics.
    - Merging relevant columns into DataFrames.

2. **Pairwise relationships between continuous variables**
    - Exploring correlations between features.
    - Creating a correlation matrix.

3. **Splitting our data**
    - Preparing features and labels.
    - Splitting the data into training and testing sets.

4. **Normalizing the feature data**
    - Using StandardScaler to normalize features.
    - Preparing data for Principal Component Analysis (PCA).

5. **Principal Component Analysis on our scaled data**
    - Applying PCA to reduce dimensionality.
    - Determining the number of components.

6. **Further visualization of PCA**
    - Plotting explained variance ratios.
    - Deciding on the number of components for dimensionality reduction.

7. **Projecting on to our features**
    - Performing PCA with chosen components.
    - Transforming training and test data using PCA.

8. **Train a decision tree to classify genre**
    - Training a decision tree classifier.
    - Predicting genre labels for test data.

9. **Compare our decision tree to a logistic regression**
    - Training a logistic regression model.
    - Comparing decision tree and logistic regression using classification reports.

10. **Balance our data for greater performance**
    - Addressing class imbalance by subsetting data.
    - Rebalancing the dataset for both genres.

11. **Does balancing our dataset improve model bias?**
    - Evaluating the impact of balancing on model bias.
    - Comparing classification reports after balancing.

12. **Using cross-validation to evaluate our models**
    - Implementing K-fold cross-validation.
    - Training models using cross-validation and comparing their performance.

## Usage

To run the code and experiments presented in this notebook, follow these steps:

1. Open the notebook in Google Colab using the provided badge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abh2050/Codes/blob/master/Song%20recommender%20from%20Audio%20Data.ipynb)

2. Execute each cell in sequence, ensuring that you have the necessary data files ('fma-rock-vs-hiphop.csv' and 'echonest-metrics.json') in your working directory.

3. Explore the data, perform analysis, and experiment with different machine learning models.

4. Feel free to modify and adapt the code for your own song recommendation projects or machine learning tasks.

## Acknowledgments

This notebook is based on a project from DataCamp and utilizes data from The Echo Nest for audio analysis.

