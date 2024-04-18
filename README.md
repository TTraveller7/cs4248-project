# cs4248-project

## Introduction
This repo contains the source code for the CS4248 Final Project by Team 51.
A0211218W, A0211207Y, A0211244X , A0218178X , A0240201H, A0239130N

**Dataset used:** [IWSLT 2017 Chinese-English data](https://huggingface.co/datasets/iwslt2017)

Please refer to our research paper for more details on this project.

## Contents
The repo consists of the following files:
* Research Paper (`team51_CS4248_Project_Report.pdf`)
* Jupyter Notebooks
    * Baseline Model + Hyperparameter Tuning (`transformer_eval_with_test_split.ipynb`)
    * Radical Processing (`radical_processing.ipynb`)
    * Document-Level Context `doc_level.ipynb`
* Sub-classed Test Data (based on notation used in Paper)
    * [idiom] `contains_idiom_sentences.json`
    * [polyphones] `contains_polyphones_sentences.json`
    * [unseen tokens] `contains_unseen_words_sentences.json`
*  External data used to subclass Test Data 
    * List of idioms used `idiom.json` (Taken from [this repo](https://github.com/pwxcoo/chinese-xinhua/tree/master/data))
    * List of polyphonic Chinese words `polyphones.json` (Taken from [this repo](https://github.com/hjzin/PolyphoneDisambiguation))
