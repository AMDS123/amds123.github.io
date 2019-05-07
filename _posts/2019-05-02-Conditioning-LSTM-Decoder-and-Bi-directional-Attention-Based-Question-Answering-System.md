---
layout: post
title: "Conditioning LSTM Decoder and Bi-directional Attention Based Question Answering System"
date: 2019-05-02 01:07:20
categories: arXiv_AI
tags: arXiv_AI Attention RNN Prediction
author: Heguang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Applying neural-networks on Question Answering has gained increasing popularity in recent years. In this paper, I implemented a model with Bi-directional attention flow layer, connected with a Multi-layer LSTM encoder, connected with one start-index decoder and one conditioning end-index decoder. I introduce a new end-index decoder layer, conditioning on start-index output. The Experiment shows this has increased model performance by 15.16%. For prediction, I proposed a new smart-span equation, rewarding both short answer length and high probability in start-index and end-index, which further improved the prediction accuracy. The best single model achieves an F1 score of 73.97% and EM score of 64.95% on test set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02019](http://arxiv.org/abs/1905.02019)

##### PDF
[http://arxiv.org/pdf/1905.02019](http://arxiv.org/pdf/1905.02019)

