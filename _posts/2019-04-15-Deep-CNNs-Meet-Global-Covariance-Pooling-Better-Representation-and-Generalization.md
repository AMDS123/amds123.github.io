---
layout: post
title: "Deep CNNs Meet Global Covariance Pooling: Better Representation and Generalization"
date: 2019-04-15 04:30:01
categories: arXiv_AI
tags: arXiv_AI Embedding CNN Classification Recognition
author: Qilong Wang, Jiangtao Xie, Wangmeng Zuo, Lei Zhang, Peihua Li
mathjax: true
---

* content
{:toc}

##### Abstract
Compared with global average pooling in existing deep convolutional neural networks (CNNs), global covariance pooling can capture richer statistics of deep features, having potential for improving representation and generalization abilities of deep CNNs. However, integration of global covariance pooling into deep CNNs brings two challenges: (1) robust covariance estimation given deep features of high dimension and small sample; (2) appropriate use of geometry of covariances. To address these challenges, we propose a global Matrix Power Normalized COVariance (MPN-COV) Pooling. Our MPN-COV conforms to a robust covariance estimator, very suitable for scenario of high dimension and small sample. It can also be regarded as power-Euclidean metric between covariances, effectively exploiting their geometry. Furthermore, a global Gaussian embedding method is proposed to incorporate first-order statistics into MPN-COV. For fast training of MPN-COV networks, we propose an iterative matrix square root normalization, avoiding GPU unfriendly eigen-decomposition inherent in MPN-COV. Additionally, progressive 1x1 and group convolutions are introduced to compact covariance representations. The MPN-COV and its variants are highly modular, readily plugged into existing deep CNNs. Extensive experiments are conducted on large-scale object classification, scene categorization, fine-grained visual recognition and texture classification, showing our methods are superior to the counterparts and achieve state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06836](http://arxiv.org/abs/1904.06836)

##### PDF
[http://arxiv.org/pdf/1904.06836](http://arxiv.org/pdf/1904.06836)

