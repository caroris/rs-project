# rs-project

This project aims to predict mode choice behaviour for individuals non-car owning households across the USA. To do so, a gradient boosting classifier is studied. First, the data is pre-processed to be ready-to-use for Hyperparameter selection. Then, hyperparameters are chosen based on a randomized search.

The "nhts_train_validate.csv" file is used and is available through the Federal Highway Administration (FHWA).

The project is not yet complete and includes two python jupyter notebooks up to now: Pre-processing.ipynb and Hyperparameters.ipynb.
It is important to first run the Pre-processing file before the Hyperparameters file.

### Expected output of the Pre-processing.ipynb file (cell 11):

X_train_validate_rev is a dataframe with the following dimension: 12906 rows x 86 columns


### Expected output of the Hyperparameters.ipynb file (cell 6):

"The obtained log loss is 0.153"
