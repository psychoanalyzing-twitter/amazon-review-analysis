
# Amazon Review Rating Classification

A project which was an assignment for our Text Analytics course @ Heriot Watt Uni. This project uses a scraped dataset of amazon reviews across various categories of items and their ratings'.

## Motivation

This project aimed to develop a ML model to accurately predict the rating given using the review's text. 

## Method and results

### Methods 
The standard NLP workflow is abided by. What was done in each step of the workflow is briefly described below:

1. **Data Exploration and Visualization**.
2. **Text Processing and Normalization**. 
3. **GridSearch over Text Vectorization Techniques and Classifiers**. Standard pre-processing- stop words are removed, tweets are tokenized, lemmatization/stemming, ... . Lemmatization and stemming and compared against a classifier, and the best one is used in the next step. 
4. **Sequence Modelling - Deep Learning**. The following text representation techniques were used and compared against each other: BOW, N-grams, TF-IDF, CBOW, Skip-gram, and the pre-trained W2V model. The classifier used for comparison was the Multinomial Naive Bayes classifier, with the main metrics of comaparison precision, recall, and f1 due to class imbalance.
5. **Topic Modelling**. The best text representation models were used in a variety of classification models: LR, Facebook's FastText, and Decision Trees. 


# Results

The best performing pipeline was 


## Repository overview

Provide an overview of the directory structure and files, for example:
    

## Libraries Used
Pandas
Numpy
MatplotLib
NLTK
SKLearn
Tensorflow 
Keras
Gensim

## Running instructions

Explain to potential users how to run/replicate your workflow. If necessary, touch upon the required input data, which secret credentials are required (and how to obtain them), which software tools are needed to run the workflow (including links to the installation instructions), and how to run the workflow.


## More resources

Point interested users to any related literature and/or documentation.


## About
Contributors: Bhavika Kaliya, Alora Tabuco and Andrea Nabua.
