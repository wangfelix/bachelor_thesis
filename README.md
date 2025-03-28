# Bachelor Thesis Project
> Trading Performance Classification Using ECG and EDA Data

## Introduction

This repository contains the code and resources for my Bachelor Thesis project. The project focuses on developing and evaluating machine learning models for trading perfromance classification using features derived from ECG and EDA signals. The primary goal is to compare different feature selection methods and classifiers to determine the best performing models, demonstrating the effectiveness of techniques from Machine Learning for this task.

## Project Structure

The project is organized into the following main directories and files:

- `data/`: Contains datasets and results.
  - `splits/`: Train/test data splits.
  - `results/`: Cross-validation and evaluation results.
  - `figures/`: Plots and visualizations.
  - `raw/`: Raw data organized in individual subfolders per session, including the otree experiment data and the HRV and EDA features in `.csv` format.
- `models/`: Saved models in `.pkl` format.
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and evaluation.
  - `01_data_preprocessing.ipynb`: Data cleaning and preprocessing.
  - `02_feature_selection.ipynb`: Initial feature space reduction.
  - `03_model_training.ipynb`: Initial model training and cross-validation.
  - `04_hyperparameter_tuning.ipynb`: Hyperparameter tuning.
  - `05_model_evaluation.ipynb`: Model evaluation and SHAP analysis.
 


## Dependencies

The project uses the following main libraries and frameworks:

- Python 3.8+
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- shap
- joblib

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/username/bachelor-thesis-project.git
   cd bachelor-thesis-project
2. Install dependencies using pip or conda.
3. Run the notebooks in ascending numerical order.
