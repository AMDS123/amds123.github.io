---
layout: post
title: "Leap-LSTM: Enhancing Long Short-Term Memory for Text Categorization"
date: 2019-05-28 01:15:11
categories: arXiv_CL
tags: arXiv_CL Sentiment Ontology RNN Classification
author: Ting Huang, Gehui Shen, Zhi-Hong Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) are widely used in the field of natural language processing (NLP), ranging from text categorization to question answering and machine translation. However, RNNs generally read the whole text from beginning to end or vice versa sometimes, which makes it inefficient to process long texts. When reading a long document for a categorization task, such as topic categorization, large quantities of words are irrelevant and can be skipped. To this end, we propose Leap-LSTM, an LSTM-enhanced model which dynamically leaps between words while reading texts. At each step, we utilize several feature encoders to extract messages from preceding texts, following texts and the current word, and then determine whether to skip the current word. We evaluate Leap-LSTM on several text categorization tasks: sentiment analysis, news categorization, ontology classification and topic classification, with five benchmark data sets. The experimental results show that our model reads faster and predicts better than standard LSTM. Compared to previous models which can also skip words, our model achieves better trade-offs between performance and efficiency.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11558](https://arxiv.org/abs/1905.11558)

##### PDF
[https://arxiv.org/pdf/1905.11558](https://arxiv.org/pdf/1905.11558)

