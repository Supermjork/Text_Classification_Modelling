# Text Classification & Modelling

Text Classification and Language Modelling, using RNN, LSTM, and Attention with PyTorch. (Large Datasets, will not be included in repository)

## Data Used

Classification Task will be using the [IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) data.

Language Modelling will be using the [Cornell Movie-Dialogue Corpus](https://www.kaggle.com/datasets/rajathmc/cornell-moviedialog-corpus) data.

Note that the data will not be within the repo due to its size (~500MB, ~23GB respectively)

## Requirements Overview

The number of required Notebooks is $3$, with each of them taking a different approach to the task.

- [ ] RNN
- [ ] LSTM
- [ ] LSTM w/Attention

## Steps

The standard steps followed for practically any NLP task.

- [ ] Preprocessing
  - [ ] Lowercasing
  - [ ] Removal of Punctuation
  - [ ] Removal of Stopwords
  - [ ] Tokenization
  - [ ] Stemming/Lemmatisation
- [ ] Word Embedding
- [ ] Comparative Analysis between models

## Libraries

Defining the libraries I will be using in this assignment.

### Preprocessing

- NLTK
- SpaCy
- re

### Word Embedding

- Gensim
- torchtext (bound to not be used due to deprication)

## Installing a Virtual Env

I'm using Python `3.12.2`

Make sure you have a virtual environment called `venv_nlp` setup for this to run in. (Make sure to be in the repository's root folder)

```ps1
# If you don't have the library for it
pip install virtualenv
```

```ps1
# Define your venv name
virtualenv venv_nlp
```

```ps1
# Activate your venv
.\venv_nlp\Scripts\activate.ps1
```

```ps1
# Once activated
# Install requirements
pip install -r .\requirements.txt
```
