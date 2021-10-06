# EPAR_sentiment_analysis
This repo evaluates the feasibility of an automated sentiment analysis tool for EPARs

## Installation

First, set up virtual environment and install from ```requirements.txt```:

    conda create --name <env> --file requirements.txt

Then activate your virtual envionment:
    
    conda activate <env>

## Instructions

The raw sentences can be cleaned using ```Data_prep.ipynb```.
The sentiment model can be found in ```Logistic_regression_model.ipynb```. It can be used independently from data cleaning.
The notebook ```Extract_sentences_from_EPARs.ipynb``` can be used to extract relevant sentences from a given EPAR.
