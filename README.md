## Automatic Extraction, Classification and Neutralization of Toxic Comments

> CS 89.21 Data Mining and Knowledge Discovery
> 
> Final Project Winter 2021
>
> Yakoob Khan, Luca C. L. Lit, Louis Murerwa, Aadil Islam

## About
> This repository contains code used to scrap tweets related to anti-asian rhetoric in March 2021. We used the Toxic Comments Classification Challenge data provided by Jigsaw/Conversational AI team on Kaggle to train classification models to filter toxic comments. Finally, we explore a simple rules-based word substitution technique to neutralize the offensive language in comments that our best classification model (BERT) predicts as toxic.

## Layout of Code Repository

    ├── Tweet-Scraping          			# Code to scrape posts using Tweepy API
    ├── checkpoints     	    			# Contain intermediate predictions
        ├── bert_model_cased_not_lowered 
    ├── data    							# Training data    
    ├── deep_learning_based_models			# BERT Classification   
    ├── style-transfer						# Text Style Transfer
    ├── README.md							
    ├── machinelearningmodles				# Sci-kit Learn Classical ML Models
    └── requirements.txt					# dependencies for reproducibility
    

## Dataset
> [Toxic Comments Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge)


## Frameworks
* Sci-kit Learn
* Pytorch
* Hugging Face Transformer's Library


## Acknowledgements
> We thank Professor Soroush Vosoughi and the Teaching Assistant team for the wonderful course on Data Mining and Knowledge Discovery (Winter 2021). 
