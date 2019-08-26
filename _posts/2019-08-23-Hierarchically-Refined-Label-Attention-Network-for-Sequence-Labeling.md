---
layout: post
title: "Hierarchically-Refined Label Attention Network for Sequence Labeling"
date: 2019-08-23 05:55:46
categories: arXiv_CL
tags: arXiv_CL Attention Embedding RNN Classification
author: Leyang Cui, Yue Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
CRF has been used as a powerful model for statistical sequence labeling. For neural sequence labeling, however, BiLSTM-CRF does not always lead to better results compared with BiLSTM-softmax local classification. This can be because the simple Markov label transition model of CRF does not give much information gain over strong neural encoding. For better representing label sequences, we investigate a hierarchically-refined label attention network, which explicitly leverages label embeddings and captures potential long-term label dependency by giving each word incrementally refined label distributions with hierarchical attention. Results on POS tagging, NER and CCG supertagging show that the proposed model not only improves the overall tagging accuracy with similar number of parameters, but also significantly speeds up the training and testing compared to BiLSTM-CRF.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08676](http://arxiv.org/abs/1908.08676)

##### PDF
[http://arxiv.org/pdf/1908.08676](http://arxiv.org/pdf/1908.08676)

