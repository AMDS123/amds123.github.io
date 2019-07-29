---
layout: post
title: "Investigating Self-Attention Network for Chinese Word Segmentation"
date: 2019-07-26 12:29:37
categories: arXiv_CL
tags: arXiv_CL Segmentation Attention Embedding RNN Prediction
author: Leilei Gan, Yue Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network has become the dominant method for Chinese word segmentation. Most existing models cast the task as sequence labeling, using BiLSTM-CRF for representing the input and making output predictions. Recently, attention-based sequence models have emerged as a highly competitive alternative to LSTMs, which allow better running speed by parallelization of computation. We investigate self attention network for Chinese word segmentation, making comparisons between BiLSTM-CRF models. In addition, the influence of contextualized character embeddings is investigated using BERT, and a method is proposed for integrating word information into SAN segmentation. Results show that SAN gives highly competitive results compared with BiLSTMs, with BERT and word information further improving segmentation for in-domain and cross-domain segmentation. Our final models give the best results for 6 heterogenous domain benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11512](http://arxiv.org/abs/1907.11512)

##### PDF
[http://arxiv.org/pdf/1907.11512](http://arxiv.org/pdf/1907.11512)

