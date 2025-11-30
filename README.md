# Butterfly Classification Analysis

This notebook analyzes butterfly species classification using deep learning embeddings and clustering techniques.

## Overview

The analysis includes:
- **Embeddings Generation**: Histogram-based and deep learning embeddings using EfficientNet-B0
- **Dimensionality Reduction**: t-SNE and PCA visualization of embedding spaces
- **Classification**: KNN and XGBoost classifiers trained on butterfly species
- **Clustering**: K-means and hierarchical clustering with ARI score evaluation

## Dataset

The dataset contains 6 butterfly species with attributes like mimicry status, palatability, and detailed notes. Data is sourced from the [Butterfly Mimics 2022 dataset](https://www.kaggle.com/datasets/keithpinson/butterfly-mimics-2022).

## Key Results

- Compares model performance on full vs. reduced embeddings
- Evaluates clustering quality against ground truth labels
- Provides visualization of classification and clustering results
