# Classification-for-Gas-Array-Drift-Dataset

# Introduction
Here, I demonstrated EDA for Gas Array drift dataset using PCA and classification using LDA. The dataset is an open source dataset from UCI ML repository. Detail: 
[Gas sensor array drift dataset] (https://archive.ics.uci.edu/ml/datasets/gas+sensor+array+drift+dataset)


Personally, I have somewhat an affinity for dataset like this since I do work with chemical sensors. Usually in my experience, although I might be biased, LDA works pretty well for things that can easily have clear discrimination (especially if you see it in PCA plot). 

# File
This repo only contains one file: the .ipynb notebook that contains how I process my data, do PCA and LDA. 

I might or might not update my jupyter notebook, depending on whether I want to test different classifiers or just do things slightly differently.

# Prerequisites
- Pandas
- Matplotlib
- Seaborn
- Sklearn

# Licensing and Acknowledgement
I do want to acknowledge the original authors for making their dataset public:
Alexander Vergara and Shankar Vembu and Tuba Ayhan and Margaret A. Ryan and Margie L. Homer and RamÃ³n Huerta, Chemical gas sensor drift compensation using classifier ensembles, Sensors and Actuators B: Chemical (2012) doi: 10.1016/j.snb.2012.01.074.

If you take a look at their paper, they did SVM with rbf kernel for classification. 

For making the dataset public and UCI ML repository for the dataset. 
