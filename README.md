# MED_SUM

A Hybrid (Extractive + Abstractive) Medical Article Summarization Model

## Overview

MED_SUM is a machine learning project aimed at generating concise and informative summaries for medical articles using a hybrid methodology—combining extractive and abstractive summarization techniques.

## Project Highlights

- **Hybrid Summarization:** Integrates extractive (selecting key sentences) and abstractive (generating novel sentences) methods for better summary quality.
- **Medical Domain Focus:** Specifically tailored for summarizing medical literature, such as research articles.
- **Code-Only Repository:** This repository contains only the code required for training and evaluating the models. No datasets, intermediate files, or final models are included due to their large size.
- **GPU Training on Kaggle:** All experiments were conducted on Kaggle using GPU resources for efficient training and evaluation.

## Dataset

- **Source:** [PubMed Article Summarization Dataset on Kaggle](https://www.kaggle.com/datasets)
- The dataset consists of medical research articles and their corresponding summaries.
- **Note:** The dataset itself is not included in this repository due to storage limitations. Please download it directly from Kaggle if you wish to reproduce the experiments.

## Evaluation Scores

The MED_SUM model was evaluated using ROUGE metrics on a sample of 100 articles from Pubmed Dataset. Below are the average scores:

- **ROUGE-1**: Precision: 0.4435, Recall: 0.3041, F-Measure: 0.3413
- **ROUGE-2**: Precision: 0.1462, Recall: 0.0989, F-Measure: 0.1115
- **ROUGE-L**: Precision: 0.2732, Recall: 0.1886, F-Measure: 0.2103

These scores indicate the model's ability to capture both the content and structure of reference summaries in the medical domain.
