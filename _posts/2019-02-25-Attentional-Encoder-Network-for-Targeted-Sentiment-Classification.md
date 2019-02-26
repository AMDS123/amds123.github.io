---
layout: post
title: "Attentional Encoder Network for Targeted Sentiment Classification"
date: 2019-02-25 14:51:46
categories: arXiv_CL
tags: arXiv_CL Regularization Sentiment Attention Sentiment_Classification Embedding RNN Classification
author: Youwei Song, Jiahai Wang, Tao Jiang, Zhiyue Liu, Yanghui Rao
mathjax: true
---

* content
{:toc}

##### Abstract
Targeted sentiment classification aims at determining the sentimental tendency towards specific targets. Most of the previous approaches model context and target words using recurrent neural networks such as LSTM in conjunction with attention mechanisms. However, LSTM networks are difficult to parallelize because of their sequential nature. Moreover, since full backpropagation over the sequence requires large amounts of memory, essentially every implementation of backpropagation through time is the truncated version, which brings difficulty in remembering long-term patterns. To address these issues, this paper propose an Attentional Encoder Network (AEN) for targeted sentiment classification. Contrary to previous LSTM based works, AEN eschews complex recurrent neural networks and employs attention based encoders for the modeling between context and target, which can excavate the rich introspective and interactive semantic information from the word embeddings without considering the distance between words. This paper also raise the label unreliability issue and introduce label smoothing regularization term to the loss function for encouraging the model to be less confident with the training labels. Experimental results on three benchmark datasets demonstrate that our model achieves comparable or superior performances with a lightweight model size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09314](http://arxiv.org/abs/1902.09314)

##### PDF
[http://arxiv.org/pdf/1902.09314](http://arxiv.org/pdf/1902.09314)

