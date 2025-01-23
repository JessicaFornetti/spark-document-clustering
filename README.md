# spark-document-clustering

This project uses Apache Spark to cluster similar documents together so that documents sharing the same theme are placed in the same group and documents on very different topics are placed in separate groups. The following dataset is used : [20 Newsgroups Dataset](http://qwone.com/~jason/20Newsgroups/).

This project was completed as part of the course Machine Learning for Data Science at University Paris Cité, France. Therefore the comments and analysis are written in French.

The main steps of the project are outlined below:

- **Spark Environment Setup** 
- **Data Preparation** : Download and extraction of the data, seperation of the body and head of the message, extraction of organization and category fields
- **Descriptive Analysis Using SQL** : SQL queries to ensure there are only 2 categories, count the different number of organizations, generate descriptive statistics based on the Date feature
- **Text Transformation** : Tokenization of the documents into lists of words followed by conversion of the tokenized text into vector representations using HashingTF
- **Document Clustering Using KMeans**
- **Clustering Improvements** : Use of TF-IDF and document vector normalization before KMeans clustering

# Repository Overview
This repository contains 1 [Jupyter notebook](SparkProject.ipynb).

