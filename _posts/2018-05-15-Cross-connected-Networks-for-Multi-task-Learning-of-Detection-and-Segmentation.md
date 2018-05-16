---
layout: post
title: "Cross-connected Networks for Multi-task Learning of Detection and Segmentation"
date: 2018-05-15 05:32:55
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Detection
author: Seiichiro Fukuda, Ryota Yoshihashi, Rei Kawakami, Shaodi You, Makoto Iida, Takeshi Naemura
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning improves generalization performance by sharing knowledge among related tasks. Existing models are for task combinations annotated on the same dataset, while there are cases where multiple datasets are available for each task. How to utilize knowledge of successful single-task CNNs that are trained on each dataset has been explored less than multi-task learning with a single dataset. We propose a cross-connected CNN, a new architecture that connects single-task CNNs through convolutional layers, which transfer useful information for the counterpart. We evaluated our proposed architecture on a combination of detection and segmentation using two datasets. Experiments on pedestrians show our CNN achieved a higher detection performance compared to baseline CNNs, while maintaining high quality for segmentation. It is the first known attempt to tackle multi-task learning with different training datasets between detection and segmentation. Experiments with wild birds demonstrate how our CNN learns general representations from limited datasets.

##### Abstract (translated by Google)
多任务学习通过在相关任务之间共享知识来提高泛化性能。现有模型用于在同一数据集上注释的任务组合，而有些情况下多个数据集可用于每个任务。如何利用在每个数据集上训练过的成功的单任务CNN的知识已经被探索，而不是单一数据集的多任务学习。我们提出了一种交叉连接的CNN，一种通过卷积层连接单任务CNN的新架构，它将相关信息传递给对方。我们使用两个数据集对检测和分割的组合进行了评估。对行人的实验表明，与基线CNN相比，我们的CNN实现了更高的检测性能，同时保持了高质量的分割。这是在检测和分割之间利用不同训练数据集来处理多任务学习的第一个已知尝试。野生鸟类的实验表明我们的CNN如何从有限的数据集中学习一般的表示。

##### URL
[http://arxiv.org/abs/1805.05569](http://arxiv.org/abs/1805.05569)

##### PDF
[http://arxiv.org/pdf/1805.05569](http://arxiv.org/pdf/1805.05569)

