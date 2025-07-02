# Project: Machine Learning Approaches for Early Prediction of hERG Channel Blockade: A Comparative Study of CatBoost and XGBoost Models

## Project Goal:

The goal of this project is to distinguish between hERG blockers and non-blockers using machine learning models. The workflow includes feature extraction from SMILES strings, hyperparameter tuning, and performance evaluation of XGBoost and CatBoost classifiers. Additionally, alternative models such as SVM and Random Forest were explored.

## Dataset:

The dataset was obtained from the pytdc package using the following command:

data = Tox(name='hERG_Karim')

'Reference: Karim, A., et al. CardioTox net: a robust predictor for hERG channel blockade based on deep learning meta-feature ensembles. J Cheminform 13, 60 (2021).'

Dataset Description: An integrated Ether-a-go-go-related gene (hERG) dataset consisting of molecular structures labelled as hERG (<10uM) and non-hERG (>=10uM) blockers in the form of SMILES strings was obtained from the DeepHIT, the BindingDB database, ChEMBL bioactivity database, and other literature. For this project, the dataset contains 13,445 data points with numerical molecular descriptors and labels (hERG vs. non-hERG blockers). 

## Task Description: 

Binary classification task: Given a drug's SMILES string, predict whether the compound is a blocker (label 1, IC₅₀ < 10 µM) or a non-blocker (label 0, IC₅₀ ≥ 10 µM).

## To download the repository and dataset, run the following command in your terminal:

'git clone https://github.com/SomayehMotevalli/SM-cdd203finalproj.git'

## Set up your virtual environment, and install packages: 

Requirements:

Python version: 3.8 or higher

Operating System: Compatible with Windows, macOS, and Linux

Recommended: Conda or virtual environment for package management

Model implementation: Jupyter notebooks, Python

## Starting the Project:

Steps:

1. Fork this Repo and clone the fork
   
2. Create a conda environment from the requirements.txt file
   
 - Activate the Conda Environment
   
 - Make sure you correctly select the interpreter path for VSCode
   
3. pip install pytdc xgboost catboost rdkit scikit-learn pandas numpy
   
4. Push to GitHub
   

