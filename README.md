# Movie Recommender System

This repository contains the implementation of an advanced movie recommender system using LightGCN in PyTorch Geometric (PyG). The system integrates message passing and embeddings from a bipartite graph of users and movies, utilizing both supervised and self-supervised learning techniques to enhance recommendation quality.

## Features

- **Graph Neural Networks**: Built using LightGCN in PyG, integrating message passing and embeddings.
- **Learning Methods**: Utilizes both supervised and self-supervised learning to improve recommendation quality.
- **Loss Functions**: Trained using BPR (Bayesian Personalized Ranking) and RMSE (Root Mean Squared Error) loss functions.
- **Optimizer**: Uses Adam optimizer with learning rate decay for optimized convergence.
- **Data Processing**: Efficiently processes and evaluates graph data with sparse matrices and edge indices.
- **Evaluation Metrics**: Uses recall, precision, and NDCG (Normalized Discounted Cumulative Gain) metrics for evaluation.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/ravindramohith/movie_recommender_system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd movie_recommender_system
   ```

## Usage

- **Supervised Learning**: 
  - The supervised learning implementation can be found in `recommender-system-using-supervised-gnn_modified.ipynb`.
  - Follow the notebook to train and evaluate the supervised recommender system.

- **Self-Supervised Learning**:
  - The self-supervised learning implementation can be found in `recommender-system-using-self-supervised-gnn_modified.ipynb`.
  - Follow the notebook to train and evaluate the self-supervised recommender system.

## Evaluation

The model performance is evaluated using the following metrics:
- **Recall**: Measures the ability of the recommender system to capture relevant items.
- **Precision**: Measures the accuracy of the recommended items.
- **NDCG**: Measures the ranking quality of the recommendations.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For any questions or suggestions, please contact me through [ravindramohith@gmail.com](https://github.com/ravindramohith).