# amazon-data-analysis
This is a project developed by Mineros DataLab aiming to (1) explore the original Amazon Movies and TV database, (2) clean and preprocess it to generate a cleaned database, which serves as a high-quality input for a recommender system, and (3) analyze and find patterns of the cleaned database, using Python, Pandas, Numpy, and NLTK.

This repository contains two ipynb files, one json.gz file, and one csv file.

The two ipynb files are:
1. "1. Preprocessing.ipynb" - This code is used to explore, clean and preprocess "db amazon original.json.gz", to create a cleaned dataset, "db amazon mineros 2.csv", which contains only high-quality records and serves as a powerful input to a recommender system.
2. "2. Data analysis.ipynb" - This code is used to analyze and find interesting indicators of "db amazon mineros 2.csv".

The unique json.gz file is:
1. "db amazon original.json.gz" - This is the original and initial Amazon Review Data (2018), specifically the one that is in "Small" subsets for experimentation, the Movies and TV category, the 5-core subset of data, extracted from: https://nijianmo.github.io/amazon/index.html

The unique csv file is:
1. "db amazon mineros 2" - This is the cleaned and preprocessed database resulting from "1. Preprocessing.ipynb".
