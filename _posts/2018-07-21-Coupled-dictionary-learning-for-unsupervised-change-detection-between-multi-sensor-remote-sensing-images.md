---
layout: post
title: "Coupled dictionary learning for unsupervised change detection between multi-sensor remote sensing images"
date: 2018-07-21 10:02:34
categories: arXiv_CV
tags: arXiv_CV Sparse Detection
author: Vinicius Ferraris, Nicolas Dobigeon, Yanna Cavalcanti, Thomas Oberlin, Marie Chabert
mathjax: true
---

* content
{:toc}

##### Abstract
Archetypal scenarios for change detection generally consider two images acquired through sensors of the same modality. However, in some specific cases such as emergency situations, the only images available may be those acquired through sensors with different characteristics. This paper addresses the problem of unsupervisedly detecting changes between two observed images acquired by different sensors. These sensor dissimilarities introduce additional issues in the context of operational change detection that are not addressed by most of classical methods. This paper introduces a novel framework to effectively exploit the available information by modeling the two observed images as a sparse linear combination of atoms belonging to an overcomplete pair of coupled dictionaries learnt from each observed image. As they cover the same geographical location, codes are expected to be globally similar except for possible changes in sparse spatial locations. Thus, the change detection task is envisioned through a dual code estimation which enforces spatial sparsity in the difference between the estimated codes associated with each image. This problem is formulated as an inverse problem which is iteratively solved using an efficient proximal alternating minimization algorithm accounting for nonsmooth and nonconvex functions. The proposed method is applied to real multisensor images with simulated yet realistic and real images. A comparison with state-of-the-art change detection methods evidences the accuracy of the proposed strategy.

##### Abstract (translated by Google)
用于变化检测的原型场景通常考虑通过相同模态的传感器获取的两个图像。然而，在诸如紧急情况的一些特定情况下，可用的唯一图像可以是通过具有不同特征的传感器获得的图像。本文讨论了无监督地检测由不同传感器获取的两个观察图像之间的变化的问题。这些传感器差异性在操作变化检测的背景下引入了大多数传统方法未解决的其他问题。本文介绍了一种新的框架，通过将两个观察到的图像建模为属于从每个观察图像学习的过度完整的耦合字典对的原子的稀疏线性组合来有效地利用可用信息。由于它们覆盖相同的地理位置，因此除了稀疏空间位置​​的可能变化之外，预期代码将在全球范围内相似。因此，通过双码估计来设想改变检测任务，该双码估计强制在与每个图像相关联的估计码之间的差异中的空间稀疏性。该问题被公式化为逆问题，其使用考虑非光滑和非凸函数的有效近端交替最小化算法来迭代地求解。所提出的方法应用于具有模拟但真实和真实图像的真实多传感器图像。与现有技术的变化检测方法的比较证明了所提出的策略的准确性。

##### URL
[http://arxiv.org/abs/1807.08118](http://arxiv.org/abs/1807.08118)

##### PDF
[http://arxiv.org/pdf/1807.08118](http://arxiv.org/pdf/1807.08118)

