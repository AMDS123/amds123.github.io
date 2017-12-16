---
layout: post
title: "CREST: Convolutional Residual Learning for Visual Tracking"
date: 2017-08-01 09:47:20
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Relation
author: Yibing Song, Chao Ma, Lijun Gong, Jiawei Zhang, Rynson Lau, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative correlation filters (DCFs) have been shown to perform superiorly in visual tracking. They only need a small set of training samples from the initial frame to generate an appearance model. However, existing DCFs learn the filters separately from feature extraction, and update these filters using a moving average operation with an empirical weight. These DCF trackers hardly benefit from the end-to-end training. In this paper, we propose the CREST algorithm to reformulate DCFs as a one-layer convolutional neural network. Our method integrates feature extraction, response map generation as well as model update into the neural networks for an end-to-end training. To reduce model degradation during online update, we apply residual learning to take appearance changes into account. Extensive experiments on the benchmark datasets demonstrate that our CREST tracker performs favorably against state-of-the-art trackers.

##### Abstract (translated by Google)
鉴别相关滤波器（DCF）已被证明在视觉追踪中表现优越。他们只需要从初始帧中的一小组训练样本来生成外观模型。然而，现有的DCF从特征提取中分别学习滤波器，并使用具有经验权重的移动平均运算来更新这些滤波器。这些DCF跟踪器很难从端到端的培训中受益。在本文中，我们提出了CREST算法，将DCF重新构造成单层卷积神经网络。我们的方法将特征提取，响应图生成以及模型更新整合到神经网络中以进行端到端训练。为了减少在线更新期间的模型退化，我们应用残差学习来考虑外观变化。在基准数据集上的大量实验表明，我们的CREST跟踪器对最先进的跟踪器表现出色。

##### URL
[https://arxiv.org/abs/1708.00225](https://arxiv.org/abs/1708.00225)

##### PDF
[https://arxiv.org/pdf/1708.00225](https://arxiv.org/pdf/1708.00225)

