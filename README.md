# NBA2k25ML
Repo containing code, data, and reports for a project demonstrating use of several supervised and unsupervised machine learning methods to achieve positional classification and identify latent archetypes and anomalies based on NBA2k25 rating data.

## current_nba_players.csv
Data file used for the analysis. The file contains biographical information, and every rating and badge for each player in the NBA 2k25 videogame. Data was sourced from Kaggle at this link: https://www.kaggle.com/datasets/reinerjasin/nba-2k25-player-complete-dataset

## eda.ipynb and edareport.docx
Jupyter notebook containing code for exploratory data analysis on the data set. Findings are reported in the Word document.

## Supervised.ipynb and SupervisedReport.pdf
Jupyter notebook containing code for supervised learning models, including each model (training, testing, etc.), tuned hyperparameters, and model selection. Findings are reported in the pdf, which was created in LaTeX format using Overleaf.

## Unsupervised.ipynb and UnsupervisedReport.pdf
Jupyter notebook containing code for unsupervised learning models, including each model (training, testing, etc.), tuned hyperparameters, and model selection. Findings are reported in the pdf, which was created in LaTeX format using Overleaf.

## umap_nba_players.csv
This file is a byproduct of the analysis. It contains the fitted UMAP projection for the data set, used to reduce dimensionality of the data, especially since there are many variables, and many are highly correlated with one another.
