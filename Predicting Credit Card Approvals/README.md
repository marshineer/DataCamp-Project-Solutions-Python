# Predicting Credit Card Approvals

## Project Description
Comparing simple machine learning models for predicting whether credit card applications will be approved. Includes handling missing values and data cleaning, as well as some model improvement.

## Contribution
Found an error in the data pre-processing where the the feature 'CreditScore' was dropped rather than 'DriversLicense', as was indicated. Discovered this had no impact on the model accuracy. Therefore, did a meta-analysis to determine which parameters are actually informative, in an attempt to simplify the model further. Realized that their model effectively uses only a single feature, and that the same accuracy was obtained by simply checking for prior defaults, and using that feature as an indicator for approval. Therefore, the solution is not improved by the machine learning implemented herein.

Implemented a simple neural network to test whether there is more hidden infomation in the data, which the previous machine learning techniques could not uncover. No clear improvement on the single feature prediction was found. Since neural nets are universal function approximators, this likely indicates that the data does not contain more information than can be predicted by the single feature 'prior defaults'.

## Setup
Python version 3.9.7
The conda environment requirements for running the project are included in the yaml file. It includes only a Jupyter notebook and the associated data. 

## Credits
This project is forked from [here](https://github.com/veeralakrishna/DataCamp-Project-Solutions-Python)