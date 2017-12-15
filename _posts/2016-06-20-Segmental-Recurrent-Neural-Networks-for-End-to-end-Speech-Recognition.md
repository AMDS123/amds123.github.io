---
layout: post
title: "Segmental Recurrent Neural Networks for End-to-end Speech Recognition"
date: 2016-06-20 10:29:23
categories: arXiv_SD
tags: arXiv_SD Segmentation Speech_Recognition RNN Language_Model Recognition
author: Liang Lu, Lingpeng Kong, Chris Dyer, Noah A. Smith, Steve Renals
mathjax: true
---

* content
{:toc}

##### Abstract
We study the segmental recurrent neural network for end-to-end acoustic modelling. This model connects the segmental conditional random field (CRF) with a recurrent neural network (RNN) used for feature extraction. Compared to most previous CRF-based acoustic models, it does not rely on an external system to provide features or segmentation boundaries. Instead, this model marginalises out all the possible segmentations, and features are extracted from the RNN trained together with the segmental CRF. In essence, this model is self-contained and can be trained end-to-end. In this paper, we discuss practical training and decoding issues as well as the method to speed up the training in the context of speech recognition. We performed experiments on the TIMIT dataset. We achieved 17.3 phone error rate (PER) from the first-pass decoding --- the best reported result using CRFs, despite the fact that we only used a zeroth-order CRF and without using any language model.

##### Abstract (translated by Google)
我们研究了用于端到端声学建模的分段递归神经网络。该模型将分段条件随机场（CRF）与用于特征提取的递归神经网络（RNN）相连接。与以前大多数基于CRF的声学模型相比，它不依赖于外部系统来提供特征或分割边界。相反，这个模型边际化了所有可能的分割，并且特征从与分段CRF一起训练的RNN中提取。实质上，这种模式是独立的，可以进行端到端的培训。在本文中，我们讨论实用的训练和解码问题以及在语音识别的背景下加速训练的方法。我们在TIMIT数据集上进行了实验。尽管事实上我们只使用零阶CRF而没有使用任何语言模型，但我们从第一次解码获得了17.3的电话差错率（PER），即使用CRF的最好的报告结果。

##### URL
[https://arxiv.org/abs/1603.00223](https://arxiv.org/abs/1603.00223)

##### PDF
[https://arxiv.org/pdf/1603.00223](https://arxiv.org/pdf/1603.00223)

