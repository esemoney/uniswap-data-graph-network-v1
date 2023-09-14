
# Uniswap Transaction Anomaly Detection

This notebook detects anomalous Uniswap transactions using a Graph Convolutional Network (GCN) on a simplified graph representation of swaps between user addresses.

The model is trained on real Uniswap swaps, with synthetic anomalies introduced by modifying amounts and timestamps for a subset of transactions.

The goal is to demonstrate skills in:

- Graph data construction
- Node and edge feature engineering
- Implementation of a basic GCN classifier
- Model evaluation using classification metrics
- Analysis of predictions as a proof of concept for applying graph neural networks to blockchain transaction anomaly detection.

## Notebooks

1. `data_processing.ipynb`: Fetch Uniswap data, sample swaps, inject anomalies, construct graph  
2. `model_training.ipynb`: GCN model implementation, training, evaluation
3. `analysis.ipynb`: Visualize and analyze predictions
