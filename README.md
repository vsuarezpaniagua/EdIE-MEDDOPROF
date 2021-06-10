# EdIE-MEDDOPROF

## Introduction
Multiple BETO classifiers for MEDDOPROF Shared Task 2021.

## Prerequisites
Following packages need to be installed:
pandas, tqdm, nltk, spacy [es_core_news_lg], tensorflow, transformers, seqeval

## Directory structure
The training and test dataset need to be in the "meddoprof_training_set" and "meddoprof_test_set" folders, respectively. "meddoprof_training_set" should contain the task1 and task2 annotations in separated folders. If you want to use additional data for training in the Task1, the train and valid ProfNER data folders need to be in ""ProfNER>DATA>subtask-2>brat".

## Installation
Install the prerequisites using "pip install".

## Usage
Run all the notebook cells modifying the parameters.

## Examples
Parameters: bioes = True (for BIOES tag)/ False (for BIO tag); task1 = True (for Task1) / False (for Task2); plus = True (use ProfNER data) / False (only MEDDOPROF data); positives = True (use only positives for training) / False (use only positives for training)

### Input / Output
Processed data will be saved in the "processedData" folder. The predictions will be saved in the "MEDDOPROF_dccuchile_bert-base-spanish-wwm-uncased>predicitions" folder (rename it before use different parameters).

## Contact
Víctor Suárez-Paniagua (vsuarezpaniagua@gmail.com).

## License

