# Movie Recommendation System

This repository contains a small movie recommendation system built for experimentation and learning. It includes datasets, exploratory notebooks, and example recommendation approaches (collaborative filtering and content-based methods).

## Contents

- data/
  - movies.csv, ratings.csv, credits.csv, movies_small.csv — datasets used for experiments
- notebooks/
  - Notebook 1.ipynb, Notebook 2.ipynb, Notebook 3.ipynb — exploratory analysis and modeling notebooks
- movie-recommenation-system.ipynb — main demo notebook
- requirements.txt — Python dependencies
- README.md — this file

## Project overview

The goal of this project is to demonstrate basic recommender-system pipelines using publicly available movie rating and metadata. Approaches explored in the notebooks include:

- Collaborative filtering (user-item matrix, matrix factorization / neighborhood methods)
- Content-based filtering (movie metadata, genres, keywords, credits)
- Popularity based filtering

The notebooks walk through data cleaning, feature engineering, building models, and evaluating recommendations with common metrics.

## Installation

1. Create and activate a Python virtual environment (recommended):

   python3 -m venv .venv
   source .venv/bin/activate

2. Install dependencies:

   pip install -r requirements.txt

## Usage

- Open the notebooks folder or the main demo notebook in Jupyter/Lab to reproduce the analyses and experiments:

   jupyter lab

- Follow the notebook cells in order. The notebooks include explanatory text, code to load data from the data/ folder, and visualization/metrics for evaluation.

## Data

The repository includes small CSV files used for demonstration. If you need larger datasets, adjust paths in the notebooks and be mindful of memory constraints.

## Evaluation

Notebooks use common recommender-system evaluation strategies and metrics (train/test splits, RMSE, precision@k, recall@k or similar) — see each notebook for details.

## Contributing

This project is a learning/demo repository. Contributions and improvements are welcome: better preprocessing, more advanced models (e.g., neural collaborative filtering), or packaging as a reusable library.
