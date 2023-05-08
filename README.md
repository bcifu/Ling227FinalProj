# Ling227FinalProj
Final Project Code for Rafi Brent, Ben Cifu, and Josephine Cureton's final project

All code is in Python Interactive Notebooks. It was originally written in Google Colab and is intended for use there (see Drive mounting and file paths). If you want to run it locally, simply replace all references to data with local file references (these are mainly in teh first four cells)

Each file is self-contained and documented. They each contain different analyses and parts of the project.

Files:
* Data_collection.ipynb is responsible for using the ChatGPT API to build the dataset
* Data_cleaner.ipynb cleans that data into a single file with one reponse on each line to be used by other files
* VocabDiversity+Bitri.ipynb contains vocabulary and lexical property analysis
* WordBigram.ipynb contains the Trigram Naive Bayes model as well as word distribution (burstiness) analysis
* POS.ipynb contains all the Part of Speach analysis: relative frequency, distribution, Naive Bayes trigram models, Hidden Markov Model, and perplexity
* Text_classification.ipynb contains the DistilBERT discriminiation model
