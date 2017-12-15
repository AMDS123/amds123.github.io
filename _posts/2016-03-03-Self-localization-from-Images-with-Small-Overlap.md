---
layout: post
title: "Self-localization from Images with Small Overlap"
date: 2016-03-03 06:39:37
categories: arXiv_CV
tags: arXiv_CV CNN
author: Tanaka Kanji
mathjax: true
---

* content
{:toc}

##### Abstract
With the recent success of visual features from deep convolutional neural networks (DCNN) in visual robot self-localization, it has become important and practical to address more general self-localization scenarios. In this paper, we address the scenario of self-localization from images with small overlap. We explicitly introduce a localization difficulty index as a decreasing function of view overlap between query and relevant database images and investigate performance versus difficulty for challenging cross-view self-localization tasks. We then reformulate the self-localization as a scalable bag-of-visual-features (BoVF) scene retrieval and present an efficient solution called PCA-NBNN, aiming to facilitate fast and yet discriminative correspondence between partially overlapping images. The proposed approach adopts recent findings in discriminativity preserving encoding of DCNN features using principal component analysis (PCA) and cross-domain scene matching using naive Bayes nearest neighbor distance metric (NBNN). We experimentally demonstrate that the proposed PCA-NBNN framework frequently achieves comparable results to previous DCNN features and that the BoVF model is significantly more efficient. We further address an important alternative scenario of "self-localization from images with NO overlap" and report the result.

##### Abstract (translated by Google)
随着近年来视觉机器人自定位中深度卷积神经网络（DCNN）的视觉特性的成功，解决更一般的自定位场景变得重要和实用。在本文中，我们从小的重叠的图像处理自我定位的情况。我们明确引入了一个局部化难度指数作为查询与相关数据库图像之间视图重叠的递减函数，并且针对挑战交叉视图自我定位任务的性能与难度进行调查。然后，我们将自我定位作为一种可扩展的视觉特征（BoVF）场景检索进行重新表达，并提出一种称为PCA-NBNN的有效解决方案，目的是促进部分重叠图像之间的快速而有区别的对应。所提出的方法采用使用主成分分析（PCA）的DCNN特征的保留区分编码和使用朴素贝叶斯最近邻距离度量（NBNN）的跨区域场景匹配的最近发现。我们通过实验证明，所提出的PCA-NBNN框架经常能够达到与以前的DCNN特性相当的结果，并且BoVF模型的效率显着提高。我们进一步解决了“无重叠图像自我定位”的重要替代方案并报告结果。

##### URL
[https://arxiv.org/abs/1603.00993](https://arxiv.org/abs/1603.00993)

##### PDF
[https://arxiv.org/pdf/1603.00993](https://arxiv.org/pdf/1603.00993)

