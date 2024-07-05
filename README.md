# Hate Speech Detection with Annotation Sensitivity Analysis

## Project Overview
This project investigates the impact of annotation perspectives on hate speech detection models using Large Language Models (LLMs). We explore how different annotation perspectives affect model performance and robustness in identifying hate speech in social media data.

## Key Features
* Analysis of different annotation perspectives (original, uncontroversial, controversial)
* Comparison of multiple pre-trained language models for hate speech detection
* Evaluation of model performance across various metrics (accuracy, F1-score, precision, recall)
* Visualisation of annotation confidence distribution
* Investigation of label noise impact on model performance

## Dataset
We use the Hate Speech and Offensive Language dataset introduced by Davidson et al. The dataset contains tweets labeled for hate speech, offensive language, and neutral content.

## Models
We evaluate and compare the following models from huggingface:
- cardiffnlp/twitter-roberta-base-hate
- tum-nlp/bert-hateXplain

## Acknowledgements
1. Davidson, T., Warmsley, D., Macy, M. and Weber, I. 2017. Automated Hate Speech Detection and the Problem of Offensive Language. Proceedings of the International AAAI Conference on Web and Social Media. 11(1), pp.512–515.
2. Barbieri, F., Camacho-Collados, J., Neves, L. and Espinosa-Anke, L. 2020. TWEETEVAL: Unified Benchmark and Comparative Evaluation for Tweet Classification [Online]. Available from: https://arxiv.org/pdf/2010.12421.‌
