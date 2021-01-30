# amazon-data-analysis
This is a project developed by Mineros DataLab aiming to (1) explore the original Amazon Review Data (2018) database, (2) clean and preprocess its numeric and textual data to generate a cleaned database, which serves as a high-quality input for a recommender system, and (3) analyze and find patterns of the cleaned database, using Python, Pandas, Numpy, and NLTK.

This repository contains two ipynb files. Besides, it should also have two databases, one as a json.gz file and the other one as a csv file, but because of their sizes, it is not possible to upload these files here. But do not worry, we will detail how to get these two datasets!

The two ipynb files are:
1. "1. Preprocessing.ipynb" - This code is used to explore, clean and preprocess "db amazon original.json.gz", to create a cleaned dataset, "db amazon mineros 2.csv", which contains only high-quality records and serves as a powerful input to a recommender system.
2. "2. Data analysis.ipynb" - This code is used to analyze and find interesting indicators of "db amazon mineros 2.csv".

The unique json.gz file should be:
1. "db amazon original.json.gz" - This is the original Amazon Review Data (2018), specifically the one that is in "Small" subsets for experimentation, the Movies and TV category, the 5-core subset of data, extracted from: https://nijianmo.github.io/amazon/index.html

The unique csv file should be:
1. "db amazon mineros 2" - This is the cleaned and preprocessed database resulting from "1. Preprocessing.ipynb". It has 500,000 records and 6 columns.
