# Detecting Helpfulness of Reviews

## Overview
In this project, we aim to build a text classification model to identify helpful reviews from a lot of product reviews.  

We used the "Helpful Sentences from Reviews" dataset, finetuned a pre-trained BERT model to achieve our goals.

In addition, we applied the Bagging algorithms of Ensemble Learning to train multiple models and combined them as an ensemble for the sake of improving the overall performance.


## Attribution
### Dataset
We have used a dataset with total 22,000 reviews from public available Amazon product reviews.
You can download the dataset from [link](https://registry.opendata.aws/helpful-sentences-from-reviews/).

### Model 
There are two models we have trained in this project. [[Download]]()
1. Standard BERT model (Trained using all training data) 
2. Ensemble models (Trained using Bootstrap Aggregating method)

## Code Files
1. `README.md` - This file.
2. `helpfulness_classification.ipynb` - A notebook to train the model.
3. `demo.ipynb` - A demo notebook for showcase .