# rs-project

## Description

This project aims to predict mode choice behaviour for individuals non-car owning households across the USA. To do so, a gradient boosting classifier is studied. First, the data is pre-processed to be ready-to-use for Hyperparameter selection. Then, hyperparameters are chosen based on a randomized search.

The "nhts_train_validate.csv" file is used and is available through the Federal Highway Administration (FHWA).

The project is not yet complete and includes two python jupyter notebooks up to now: Pre-processing.ipynb and Hyperparameters.ipynb.


**It is important to first run the Pre-processing file before the Hyperparameters file.**

### Expected output of the Pre-processing.ipynb file (cell 11):

X_train_validate_rev is a dataframe with the following dimension: 12906 rows x 86 columns


### Expected output of the Hyperparameters.ipynb file (cell 6):

"The obtained log loss is 0.153"


### IMPORTANT: Remember to activate the environment

After cloning this repository, cd into the folder on your local device.

Then create the environment by typing the following code into your GitBash terminal:


conda env create -f environment.yml


Once the environment is created and the packages are installed, activate the environment in order to successfully run the scrips through Jupyter Notebook.

The environment name is: "rs-project-env"


More information can be found in the Conda documentation:

https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## Getting started

The code can be run with Python 3.8.

## Author

Caroline Risous - caroline.risoud@epfl.ch

## Version history

0.1 Initial Release

## License

CC-BY-4.0


