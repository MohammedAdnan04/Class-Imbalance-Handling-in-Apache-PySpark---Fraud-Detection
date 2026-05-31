# Class Imbalance Handling in Apache PySpark — Fraud Detection

## Overview
This project tackles the problem of class imbalance in financial fraud detection using Apache PySpark. It was completed as a group coursework project for COMP4124 (Big Data) at the University of Nottingham. The dataset used is PaySim1, a synthetic financial transaction dataset where fraudulent transactions are a small minority of the data.

## My Contribution
- Implemented a GBTClassifier (Gradient Boosted Trees) pipeline in PySpark
- Developed custom distributed sampling techniques including oversampling and undersampling strategies to handle class imbalance
- Designed and ran scalability experiments at varying dataset sizes to measure pipeline performance

## Project Deliverables
- IEEE-format research paper
- Fully documented PySpark notebook
- Individual presentation

## Tech Stack
- Python
- Apache PySpark
- Google Colab / Jupyter Notebook

## Dataset
- PaySim1 — synthetic mobile money transaction dataset
- Available on Kaggle: https://www.kaggle.com/datasets/ealaxi/paysim1

## How to Run
1. Clone this repository
2. Open the `.ipynb` notebook in Google Colab or a Jupyter environment with PySpark installed
3. Upload or link the PaySim1 dataset
4. Run cells sequentially from top to bottom

## Results
Scalability experiments were conducted at multiple dataset sizes to evaluate how the pipeline performs under varying data volumes. Results and analysis are documented in the notebook and the IEEE paper included in this repo.

## Module
COMP4124 — Big Data
University of Nottingham, 2024–2025
