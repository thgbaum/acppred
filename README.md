# acppred

By thgbaum

a tool to predict anticancer peptides

## Setup


$ make setup
"""
Either creates or updatades the environment
"""

##Template Folder

templates/__ini__.py
"""
Imports python scripts from this folder to act as packages
"""

templates/models.py
"""
Creates class Model where methods __init__(), transform(), train(), predict(), save() and load() are defined
"""

templates/predict.py
"""
Parses through fasta files, makes predictions and save them on a .csv file
"""

templates/server.py
"""
Creates a Flask app and links routes to reference .html files
"""

tests/test_model.py
"""
contains the methods used for testing the program. Those functions are going to be tested by pytest
"""
