# Anomaly Detection and Cluster Evaluation with PyCaret and KMeans

This project demonstrates how to perform anomaly detection using multiple algorithms available in the PyCaret library. It also evaluates the clustering quality of the cleaned data (non-anomalous points) using KMeans and calculates silhouette scores to assess the clustering performance.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
  - [1. Load Dataset](#1-load-dataset)
  - [2. Setup Environment](#2-setup-environment)
  - [3. Evaluate Models](#3-evaluate-models)
- [Results](#results)
- [License](#license)

## Overview

The script uses PyCaret to evaluate several anomaly detection models, calculates the number of anomalies detected by each model, and extracts their parameters. It then removes the detected anomalies and clusters the cleaned data using KMeans. The quality of clustering is assessed using the silhouette score for each anomaly detection model.

## Features

- Implements multiple anomaly detection models from PyCaret:
  - ABOD
  - Cluster
  - COF
  - IForest
  - Histogram
  - KNN
  - LOF
  - SVM
  - PCA
  - MCD
  - SOD
  - SOS
- Extracts and compares:
  - Number of anomalies detected by each model.
  - Parameters of each model.
  - Clustering quality (silhouette score) after removing anomalies.

## Requirements

- Python 3.x
- PyCaret
- scikit-learn
