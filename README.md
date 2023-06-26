
# Amazon Review Rating Classification

A project which was an assignment for our Text Analytics course @ Heriot Watt Uni. This project uses a scraped dataset of amazon reviews across various categories of items and their ratings'.

## Motivation

This project aimed to develop a ML model to accurately predict the rating given using the review's text. 

## Method and results

### Methods 
The standard NLP workflow is abided by. What was done in each step of the workflow is briefly described below:

1. **Data Exploration and Visualization**.
2. **Text Processing and Normalization**. 
3. **GridSearch over Text Vectorization Techniques and Classifiers**. 
4. **Sequence Modelling - Deep Learning**. 
5. **Topic Modelling**. 


# Results

The best performing model was a bidirectional LSTM with Word2Vec embedding.


## Repository overview

- results Folder: Contains the saved models so they can be re-evaluated.
- cw2.ipynb: The Jupyter Notebook containing the entire pipeline and experimentation.
- train.pickle: The pickle file containing the dataset.

    

## Libraries Used
Pandas
Numpy
MatplotLib
NLTK
SKLearn
Tensorflow 
Keras
Gensim



## About
Contributors: Bhavika Kaliya, Alora Tabuco and Andrea Nabua.
