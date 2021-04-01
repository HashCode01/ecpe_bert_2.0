
# ECPE_Bert_2.0: Emotion-Cause Pair Extraction based on Joint Two-Dimensional Representation, Interaction and Prediction

This repository contains the code for our modified EPCE_Bert model:


Base paper Used: 

Zixiang Ding, Rui Xia, Jianfei Yu. ECPE-2D: Emotion-Cause Pair Extraction based on Joint Two-Dimensional Representation, Interaction and Prediction. ACL 2020. [[pdf](https://www.aclweb.org/anthology/2020.acl-main.288.pdf)]


## Dependencies

- **Python 2** (tested on python 2.7.15)
- [Tensorflow](https://github.com/tensorflow/tensorflow) 1.13.1
- Bert (The pretrained bert model "[BERT-Base, uncased](https://storage.googleapis.com/bert_models/2020_02_20/uncased_L-12_H-768_A-12.zip)" is required. Our model is built based on
this implementation: https://github.com/google-research/bert) 

## Usage

- For ECPE_Bert_2.0(Indep, Inter-CE, Inter-EC) models, run:
    - python main.py


- For ECPE_Bert_2.0(Inter-EC(BERT)) models, run:
    - python Bert_main.py
