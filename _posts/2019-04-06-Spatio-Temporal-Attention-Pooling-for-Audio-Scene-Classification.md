---
layout: post
title: "Spatio-Temporal Attention Pooling for Audio Scene Classification"
date: 2019-04-06 22:49:20
categories: arXiv_SD
tags: arXiv_SD Attention CNN Classification
author: Huy Phan, Oliver Y. Ch&#xe9;n, Lam Pham, Philipp Koch, Maarten De Vos, Ian McLoughlin, Alfred Mertins
mathjax: true
---

* content
{:toc}

##### Abstract
Acoustic scenes are rich and redundant in their content. In this work, we present a spatio-temporal attention pooling layer coupled with a convolutional recurrent neural network to learn from patterns that are discriminative while suppressing those that are irrelevant for acoustic scene classification. The convolutional layers in this network learn invariant features from time-frequency input. The bidirectional recurrent layers are then able to encode the temporal dynamics of the resulting convolutional features. Afterwards, a two-dimensional attention mask is formed via the outer product of the spatial and temporal attention vectors learned from two designated attention layers to weigh and pool the recurrent output into a final feature vector for classification. The network is trained with between-class examples generated from between-class data augmentation. Experiments demonstrate that the proposed method not only outperforms a strong convolutional neural network baseline but also sets new state-of-the-art performance on the LITIS Rouen dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03543](http://arxiv.org/abs/1904.03543)

##### PDF
[http://arxiv.org/pdf/1904.03543](http://arxiv.org/pdf/1904.03543)

