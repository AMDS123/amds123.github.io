---
layout: post
title: "Team EP at TAC 2018: Automating data extraction in systematic reviews of environmental agents"
date: 2019-01-07 21:49:51
categories: arXiv_CL
tags: arXiv_CL Regularization Review Embedding RNN Deep_Learning
author: Artur Nowak, Pawe&#x142; Kunstman
mathjax: true
---

* content
{:toc}

##### Abstract
We describe our entry for the Systematic Review Information Extraction track of the 2018 Text Analysis Conference. Our solution is an end-to-end, deep learning, sequence tagging model based on the BI-LSTM-CRF architecture. However, we use interleaved, alternating LSTM layers with highway connections instead of the more traditional approach, where last hidden states of both directions are concatenated to create an input to the next layer. We also make extensive use of pre-trained word embeddings, namely GloVe and ELMo. Thanks to a number of regularization techniques, we were able to achieve relatively large capacity of the model (31.3M+ of trainable parameters) for the size of training set (100 documents, less than 200K tokens). The system's official score was 60.9% (micro-F1) and it ranked first for the Task 1. Additionally, after rectifying an obvious mistake in the submission format, the system scored 67.35%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02081](http://arxiv.org/abs/1901.02081)

##### PDF
[http://arxiv.org/pdf/1901.02081](http://arxiv.org/pdf/1901.02081)

