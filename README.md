# My ML Project

This is a simple machine learning sandbox project.  
The goal is to practice the full workflow:

1. Load and explore data
2. Clean and preprocess it
3. Train a basic model
4. Evaluate and improve it

## Project structure

- `data/`
  - `raw/` – Original datasets (do not modify these files).
  - `processed/` – Cleaned data ready for modeling.
- `notebooks/` – Jupyter notebooks for exploration and experiments.
- `src/` – Python code for data loading, preprocessing, and modeling.
- `scripts/` – Shell scripts to run common tasks (like training a model).
- `tests/` – Simple tests to check that code works as expected.

## Setup

### 1. Create the conda environment

```bash
conda env create -f environment.yml
conda activate my-ml-project
