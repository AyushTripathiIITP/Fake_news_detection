# Fake News Detection with BERT
This folder contains code for a fake news detection model using BERT (Bidirectional Encoder Representations from Transformers). The model is trained on a dataset containing both real and fake news articles.

#Dataset Links:
1. https://www.kaggle.com/datasets/sadikaljarif/fake-news-detection-dataset-english
2. https://www.kaggle.com/datasets/sadikaljarif/wodcloud-twiter-pic

# Table of Contents
1. Introduction
2. Requirements
3. Installation
4. Usage
5. Data Analysis
6. Model Training
7. Results

# Introduction
Fake news detection is a critical task in today's information age. This project aims to build a model using BERT, a powerful transformer-based language model, to distinguish between real and fake news articles.

# Requirements
1. Python 3.x
2. TensorFlow
3. Transformers library
4. Pandas
5. Matplotlib
6. Seaborn
7. WordCloud

# Installation
pip install -r requirements.txt

# Usage
Mainly Used for DEtecting fake news

# Data Analysis
The dataset is analyzed to gain insights into the distribution of real and fake news articles. Visualization tools such as bar charts and word clouds are used to represent the data.

# Model Training
The BERT model is fine-tuned on the dataset for the task of binary classification (real or fake). The training process involves tokenization, model architecture setup, and optimization.

# Results
The model gave result f about 99.7% , graphs have been plotted to show that model is neither underfitted or overfittted


