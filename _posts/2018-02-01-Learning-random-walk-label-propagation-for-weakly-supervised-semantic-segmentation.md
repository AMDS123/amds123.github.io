---
layout: post
title: "Learning random-walk label propagation for weakly-supervised semantic segmentation"
date: 2018-02-01 19:44:45
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Semantic_Segmentation
author: Paul Vernaza, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale training for semantic segmentation is challenging due to the expense of obtaining training data for this task relative to other vision tasks. We propose a novel training approach to address this difficulty. Given cheaply-obtained sparse image labelings, we propagate the sparse labels to produce guessed dense labelings. A standard CNN-based segmentation network is trained to mimic these labelings. The label-propagation process is defined via random-walk hitting probabilities, which leads to a differentiable parameterization with uncertainty estimates that are incorporated into our loss. We show that by learning the label-propagator jointly with the segmentation predictor, we are able to effectively learn semantic edges given no direct edge supervision. Experiments also show that training a segmentation network in this way outperforms the naive approach.

##### Abstract (translated by Google)
由于相对于其他视觉任务获得用于该任务的训练数据的花费，大规模的语义分割训练是具有挑战性的。我们提出了一种新颖的培训方法来解决这个难题。鉴于廉价获得的稀疏图像标签，我们传播稀疏标签产生猜测密集的标签。一个标准的基于CNN的分割网络被训练来模仿这些标签。标签传播过程是通过随机行走命中概率来定义的，这导致了一个可微参数化的不确定性估计值，并被纳入到我们的损失中。我们表明，通过与分词预测器共同学习标签传播者，我们能够有效地学习没有直接边缘监督的语义边缘。实验还表明，以这种方式训练分割网络胜过了朴素的方法。

##### URL
[https://arxiv.org/abs/1802.00470](https://arxiv.org/abs/1802.00470)

##### PDF
[https://arxiv.org/pdf/1802.00470](https://arxiv.org/pdf/1802.00470)

