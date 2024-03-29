# Hate Speech Spreader Detection
Hate Speech Spreader Detection on the PAN-AP-2021 dataset.

## Overview
The University of Bologna (UniBo) Natural Language Processing (NLP) project. In this project, we utilised the PAN-AP-2021 dataset to profile hate speech spreaders on social media, more specifically on Twitter, addressing the problem in English. 

Four different methods (SVM, BiLSTM, BiGRU, and BERTweet) were trained and evaluated on the dataset. Our results show that the BERTweet transformer method produces the best results in terms of accuracy on the test set.  

The steps taken are described in detail in the [Report](https://github.com/annafabris/Hate-Speech-Spreader-Detection/blob/main/Report.pdf). The slides used for the [Presentation](https://github.com/annafabris/Hate-Speech-Spreader-Detection/blob/main/Presentation.pdf) are also available.

The code may also be viewed directly from the [Notebook](https://github.com/annafabris/Hate-Speech-Spreader-Detection/blob/main/main.ipynb).

## Authors
- [Anna Fabris](https://github.com/annafabris)
- [Miki Mizutani](https://github.com/mikimizutani)
- [Leonidas Gee](https://github.com/LeonidasY)

## Results
The table below shows the accuracy on the test dataset using the four different models and their respective encodings.

|     Method     | Test Accuracy |
|:--------------:|:-------------:|
| TF-IDF + SVM   |          76.0 |
| GLoVe + BiLSTM |          64.0 |
| GLoVe + BiGRU  |          67.0 |
| BERTweet       |          78.0 |
