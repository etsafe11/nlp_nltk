**Introduction to NLP**
----------

**Overview**
In this workshop, we'll learn different Natural Language Techniques needed to start building different models. `Python3` is the preferred language for the labs. Some pre-requisites before getting started are listed below.

----------
**Pre-requisites**

 - `Python >3.0`
 - `NLTK package`
 - `Spacy`
 - `Pandas`
 - `iPython`
 - `iPython Notebook`
 - `virtualenv`

Once `python3` is installed, create and activate a `virtualenv`

    pip install virtualenv
    virtualenv -p python3 venv
    source activate venv/bin/activate
    pip install --upgrade pip
This activates a `virtualenv` where you can install the required packages

Install nltk models

    python -m nltk.downloader stopwords


Install spacy models

    python -m spacy download en

----------


**Labs**

 1. [Preprocessing](https://github.com/bibinr/SAIM-IntroductionToNLP/blob/master/Lab-1-Preprocessing/Lab-1-preprocess.ipynb) 
 2. [Part of speech tagging](https://github.com/bibinr/SAIM-IntroductionToNLP/blob/master/Lab-2-PartOfSpeech/Lab-2-PartOfSpeech.ipynb)
 3. [BOW/TF-IDF](https://github.com/bibinr/SAIM-IntroductionToNLP/blob/master/Lab-3-BOW-TFIDF/Lab-3-Bow-TFIDF.ipynb)

