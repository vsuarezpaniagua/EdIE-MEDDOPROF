# EdIE-MEDDOPROF

## Introduction
Multiple BETO classifiers and approximate string matching for MEDDOPROF Shared Task 2021.

## Prerequisites
Following packages need to be installed:
_pandas, tqdm, nltk, spacy [es_core_news_lg], tensorflow, transformers, seqeval_

## Directory structure
The training and test sets need to be in the "_meddoprof_training_set_" and "_meddoprof_test_set_" folders, respectively. "_meddoprof_training_set_" should contain the task1 and task2 annotations in separated folders. If you want to use additional data for training in Task1, the train and valid ProfNER data folders need to be in "_ProfNER>DATA>subtask-2>brat_".

## Installation
Install the prerequisites using "_pip install_".

## Usage
Run all the notebook cells modifying the parameters.

## Examples
Parameters:

_bioes = True_ (for BIOES tag)/ _False_ (for BIO tag);

_task1 = True_ (for Task1) / _False_ (for Task2);

_plus = True_ (use ProfNER data) / _False_ (only MEDDOPROF data);

_positives = True_ (use only positives for training) / _False_ (use only positives for training);

## Input / Output
Processed data will be saved in the "_processedData_" folder. The predictions will be saved in the "_MEDDOPROF_dccuchile_bert-base-spanish-wwm-uncased>predicitions_" folder (rename it before using different parameters).

## Contact
Víctor Suárez-Paniagua (vsuarezpaniagua@gmail.com).

## License
MIT License.
