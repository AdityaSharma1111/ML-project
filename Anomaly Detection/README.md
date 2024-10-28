# Anomaly Detection Using Multivariate Gaussian Distribution

This project implements an anomaly detection model using a multivariate Gaussian distribution to detect outliers in a dataset by identifying points that deviate from normal feature patterns.

## Model Overview
1. **Gaussian Estimation**: Calculates mean and variance for dataset features.
2. **Probability Density**: Uses the multivariate Gaussian distribution to estimate probability densities.
3. **Threshold Selection**: Finds the best probability threshold to detect anomalies based on F1 score from a validation set.
4. **Model Evaluation**: Measures accuracy, precision, recall, and F1 score.

## Requirements
- Python 3.x
- `numpy` and `matplotlib`

Install dependencies with:
```bash
pip install numpy matplotlib
