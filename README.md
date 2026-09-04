# Popularity Bias in Two-Tower Models: Experiments

Code accompanying the paper *"Theoretical Grounds for Popularity Bias in
Two-Tower Models Trained with Cosine-Based Loss"*.

Each notebook `<N>experiment.ipynb` reproduces Experiment N of the paper.
The first cell of every notebook states its exact configuration (towers,
loss, optimizer).

## Setup

```bash
pip install -r requirements.txt
```

Experiments 0–7 use a small synthetic dataset generated in-notebook and
need no downloads.

Experiments 8, 9 and 10 use MovieLens-32M, which must be downloaded
separately from https://grouplens.org/datasets/movielens/32m/ and
unpacked **next to** this repository:

    parent/
    ├── ml-32m/            <- unzipped MovieLens-32M (ratings.csv, ...)
    └── popularity_bias/   <- this repository

## Data

F. M. Harper and J. A. Konstan. The MovieLens Datasets: History and
Context. ACM TiiS, 2015.
