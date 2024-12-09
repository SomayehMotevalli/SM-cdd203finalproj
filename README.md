•	A README detailing data sources, virtual environment setup, and package installation for result reproduction. Where is the data 
•	●  How to download your repo 
•	●  Explain how we can set up your virtual environment, and install 
•	packages similar to the readme content provided for assignments 
•	Ensure you have code for us to run to reproduce your results 
![image](https://github.com/user-attachments/assets/788cef5b-ab0d-4004-8742-bc6c1974d7e3)
Project: Pridicting hERG and non-hERG blockers 
Project Goal:
The goal of this project is distinguishing between hERG and non-hERG blockers using machine learning models. The project involves feature extraction from SMILES strings, hyperparameter tuning, and performance evaluation of XGBoost and CatBoost classifiers.
Dataset:

where is the dataset?  The dataset is from the pytdc package. 
data = Tox(name = 'hERG_Karim')
Reference: Karim, A., et al. CardioTox net: a robust predictor for hERG channel blockade based on deep learning meta-feature ensembles. J Cheminform 13, 60 (2021).

Dataset Description: An integrated Ether-a-go-go-related gene (hERG) dataset consisting of molecular structures labelled as hERG (<10uM) and non-hERG (>=10uM) blockers in the form of SMILES strings was obtained from the DeepHIT, the BindingDB database, ChEMBL bioactivity database, and other literature. For this project, the dataset contains 13,445 data points with numerical molecular descriptors and labels (hERG vs. non-hERG blockers). 

Task Description: Binary classification. Given a drug SMILES string, predict whether it blocks (1, <10uM) or not blocks (0, >=10uM).
How to download your repository? Download the dataset from https://github.com/SomayehMotevalli/SM-cdd203finalproj.git
Starting the Project
Steps:
1. Fork this Repo and clone the fork
2. Create a conda environment from the requirements.txt file 


