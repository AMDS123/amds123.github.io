---
layout: post
title: "Brute-Force Facial Landmark Analysis With A 140,000-Way Classifier"
date: 2018-02-06 03:20:41
categories: arXiv_CV
tags: arXiv_CV Classification
author: Mengtian Li, Laszlo Jeni, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple approach to visual alignment, focusing on the illustrative task of facial landmark estimation. While most prior work treats this as a regression problem, we instead formulate it as a discrete $K$-way classification task, where a classifier is trained to return one of $K$ discrete alignments. One crucial benefit of a classifier is the ability to report back a (softmax) distribution over putative alignments. We demonstrate that this distribution is a rich representation that can be marginalized (to generate uncertainty estimates over groups of landmarks) and conditioned on (to incorporate top-down context, provided by temporal constraints in a video stream or an interactive human user). Such capabilities are difficult to integrate into classic regression-based approaches. We study performance as a function of the number of classes $K$, including the extreme "exemplar class" setting where $K$ is equal to the number of training examples (140K in our setting). Perhaps surprisingly, we show that classifiers can still be learned in this setting.

##### Abstract (translated by Google)
我们提出了一种简单的视觉对齐方法，重点是面部标志估计的说明性任务。尽管大多数先前的工作将其视为一个回归问题，但是我们将其作为一个离散的$ K $ -way分类任务来制定，其中分类器被训练为返回$ K $离散对齐之一。分类器的一个关键好处是能够报告（softmax）分布在推定的路线。我们证明，这种分配是一种可以被边缘化的丰富的表示形式（为了产生关于一组地标的不确定性估计）并且以（由视频流中的时间约束或者交互式人类用户提供的自上而下的上下文）为条件。这样的功能很难整合到经典的基于回归的方法中。我们研究性能作为类数$ K $的函数，其中包括极端的“样本类”设置，其中$ K $等于训练样例数（在我们的设置中为140K）。也许令人惊讶的是，我们表明分类器仍然可以在这个环境中学习。

##### URL
[http://arxiv.org/abs/1802.01777](http://arxiv.org/abs/1802.01777)

##### PDF
[http://arxiv.org/pdf/1802.01777](http://arxiv.org/pdf/1802.01777)

