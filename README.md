# ACPPred

By thgbaum

a tool to predict anticancer peptides

## Setup


$ make setup -> Either creates or updatades the environment


## ACPPred Folder:

acppred/__ini__.py -> Imports python scripts from this folder to act as packages

acppred/models.py -> Creates class Model where methods __init__(), transform(), train(), predict(), save() and load() are defined

acppred/predict.py -> Parses through fasta files, makes predictions and save them on a .csv file

acppred/server.py -> Creates a Flask app and links routes to reference .html files

acppred/train.py -> Sets up argument_parser arguments and stablishes tool default files Imports model and applies Random Forest estimator as default machine learning training algorithm

acppred/utils.py -> Holds amino acid one letter code


## Data Folder:

data/models -> Contains model.pickle archive

data/raw -> Contains positive.txt and negative.txt. Those files are used as training data for this platform 


## Test Folder:

tests/test_model.py -> contains the methods used for testing the program, which will be executed by pytest while testing. 


