---
layout: post
title: "Deep Domain Adaptation by Geodesic Distance Minimization"
date: 2017-10-10 20:26:55
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Yifei Wang, Wen Li, Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new approach called Deep LogCORAL for unsupervised visual domain adaptation. Our work builds on the recently proposed Deep CORAL method, which proposed to train a convolutional neural network and simultaneously minimize the Euclidean distance of convariance matrices between the source and target domains. We propose to use the Riemannian distance, approximated by Log-Euclidean distance, to replace the naive Euclidean distance in Deep CORAL. We also consider first-order information, and minimize the distance of mean vectors between two domains. We build an end-to-end model, in which we minimize both the classification loss, and the domain difference based on the first and second order information between two domains. Our experiments on the benchmark Office dataset demonstrate the improvements of our newly proposed Deep LogCORAL approach over the Deep CORAL method, as well as further improvement when optimizing both orders of information.

##### Abstract (translated by Google)
在本文中，我们提出了一种称为Deep LogCORAL的新方法，用于无监督视觉领域适应。我们的工作建立在最近提出的Deep CORAL方法上，该方法提出训练卷积神经网络，同时使源和目标域之间的协方差矩阵的欧几里得距离最小。我们建议使用由Log-Euclidean距离近似的黎曼距离来代替Deep CORAL中朴素的Euclidean距离。我们也考虑一阶信息，并最小化两个域之间的平均向量的距离。我们建立了一个端到端的模型，在这个模型中，我们根据两个域之间的一阶和二阶信息来最小化分类损失和域差异。我们在基准Office数据集上进行的实验证明了我们新提出的Deep CORCAL方法在Deep CORAL方法上的改进，以及在优化两个信息顺序时的进一步改进。

##### URL
[https://arxiv.org/abs/1707.09842](https://arxiv.org/abs/1707.09842)

##### PDF
[https://arxiv.org/pdf/1707.09842](https://arxiv.org/pdf/1707.09842)

