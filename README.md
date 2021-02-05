# Term-Extraction-With-Language-Models
## Description

## Requirements
* transformers v.4.2.2
* torch v.1.7.0+cu101
* sentencepiece v.0.1.95
* sklearn v.0.24.1
* nltk v.3.2.5
* spacy v.2.2.4
* sacremoses v.0.0.43
* pandas v.1.1.5
* numpy v.1.19.5


## Dataset

## Results

F1 Scores of the trained models.

Training | Test | Sequence Classifier | Token Classifier
------------ | ------------- | -------------|-------------
EN | EN | 45.2 | 58.3
FR | EN | 44.7 | 44.2
NL | EN | 35.9 | 58.3
ALL | EN | 46.0 | 56.2
| | | 
EN | FR | 48.1 | 57.6
FR | FR | 46.0 | 52.9
NL | FR | 40.0 | 54.5
ALL | FR | 46.7 | 55.3
| | | 
EN | NL | 58.0 | 69.8
FR | NL | 56.1 | 61.4
NL | NL | 48.5 | 69.6
ALL | NL | 56.0 | 67.8



## Hyperparameter

### Sequence Classifier
* optimizer: Adam
* learning rate: 2e-5
* batch size: 64
* epochs: 3

### Token Classifier 
* optimizer: Adam
* learning rate: 2e-5
* batch size: 8
* epochs: 2 (load best model at the end evaluating the model every 100 steps)


## Reference




