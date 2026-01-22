# Tennis Match Prediction
This project predicts the winner of ATP tennis matches using machine learning models
(XGBoost, Random Forest, and Neural Networks). 

## Project overview
The goal of this project is to evaluate whether machine learning models can outperform
professional betting odds by predicting match outcomes based on the data of historical profssional tennis matches (ATP).

## Data
- Historical ATP match data (2000–2024)
- Features include Elo ratings, surface performance, age, winner/loser and more.
- Odds data from bet365 (2024)
ATP match data from 2000-2023 is used for training.
ATP match data from 2024 is used for testing.
Odds data from bet365 (2024) is used for testing

## Models
### File: tennis_pytorch_no_embeddings_last
- Neural Network (PyTorch)
### File: tennis_scikit_randomforest_og_XGBoost
- Random Forest (scikit-learn)
- XGBoost (xgboost)

## Installation
Create the conda environment:
- conda env create -f environment.yml
- conda activate tennis-ml

## Code structure
tennis_pytorch_no_embeddings_last.ipynb
- Neuralt netværk: feature‑engineering, training og testing

tennis_scikit_randomforest og XGBoost.ipynb
- Baseline‑models: Random Forest og XGBoost

environment.yml
- Conda‑environment

*.csv
- Datafiles

Den_rigtige_parametre_test.xlsx
- Hyperparameter analysis

### Important!
Collect atp_matches_2000.csv, atp_matches_2001.csv, ... , atp_maches_2023.csv in af folder called "atp_matches"




