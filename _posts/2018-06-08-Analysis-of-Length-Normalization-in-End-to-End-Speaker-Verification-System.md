---
layout: post
title: "Analysis of Length Normalization in End-to-End Speaker Verification System"
date: 2018-06-08 15:09:14
categories: arXiv_SD
tags: arXiv_SD Embedding Classification
author: Weicheng Cai, Jinkun Chen, Ming Li
mathjax: true
---

* content
{:toc}

##### Abstract
The classical i-vectors and the latest end-to-end deep speaker embeddings are the two representative categories of utterance-level representations in automatic speaker verification systems. Traditionally, once i-vectors or deep speaker embeddings are extracted, we rely on an extra length normalization step to normalize the representations into unit-length hyperspace before back-end modeling. In this paper, we explore how the neural network learn length-normalized deep speaker embeddings in an end-to-end manner. To this end, we add a length normalization layer followed by a scale layer before the output layer of the common classification network. We conducted experiments on the verification task of the Voxceleb1 dataset. The results show that integrating this simple step in the end-to-end training pipeline significantly boosts the performance of speaker verification. In the testing stage of our L2-normalized end-to-end system, a simple inner-product can achieve the state-of-the-art.

##### Abstract (translated by Google)
经典的i向量和最新的端到端深度扬声器嵌入是自动说话人验证系统中两种代表性的话语级表示类别。传统上，一旦i矢量或深层扬声器嵌入被提取，我们就依靠额外长度归一化步骤来将表示归一化为单位长度超空间，然后再进行后端建模。在本文中，我们探讨了神经网络如何以端对端的方式学习长度归一化深度说话人嵌入。为此，我们在公共分类网络的输出层之前添加一个长度规范化层，后面跟着一个规模层。我们对Voxceleb1数据集的验证任务进行了实验。结果表明，将这一简单步骤集成到端到端训练流程中可显着提高说话者验证的性能。在我们L2规范化的端到端系统的测试阶段，一个简单的内部产品可以实现最先进的技术。

##### URL
[http://arxiv.org/abs/1806.03209](http://arxiv.org/abs/1806.03209)

##### PDF
[http://arxiv.org/pdf/1806.03209](http://arxiv.org/pdf/1806.03209)

