---
layout: post
title: "Weakly-Supervised Semantic Segmentation by Iteratively Mining Common Object Features"
date: 2018-06-12 17:42:10
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Semantic_Segmentation Classification
author: Xiang Wang, Shaodi You, Xi Li, Huimin Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly-supervised semantic segmentation under image tags supervision is a challenging task as it directly associates high-level semantic to low-level appearance. To bridge this gap, in this paper, we propose an iterative bottom-up and top-down framework which alternatively expands object regions and optimizes segmentation network. We start from initial localization produced by classification networks. While classification networks are only responsive to small and coarse discriminative object regions, we argue that, these regions contain significant common features about objects. So in the bottom-up step, we mine common object features from the initial localization and expand object regions with the mined features. To supplement non-discriminative regions, saliency maps are then considered under Bayesian framework to refine the object regions. Then in the top-down step, the refined object regions are used as supervision to train the segmentation network and to predict object masks. These object masks provide more accurate localization and contain more regions of object. Further, we take these object masks as initial localization and mine common object features from them. These processes are conducted iteratively to progressively produce fine object masks and optimize segmentation networks. Experimental results on Pascal VOC 2012 dataset demonstrate that the proposed method outperforms previous state-of-the-art methods by a large margin.

##### Abstract (translated by Google)
图像标签监控下的弱监督语义分割是一项具有挑战性的任务，因为它直接将高级语义与低级外观联系起来。为弥补这一差距，本文提出了一种迭代自下而上和自上而下的框架，它可以扩展目标区域，优化分割网络。我们从分类网络的初始本地化开始。尽管分类网络只对小的和粗略的区分对象区域有反应，但我们认为，这些区域包含关于对象的重要共同特征。因此，在自下而上的步骤中，我们从初始本地化中挖掘常见的对象特征，并使用挖掘的特征扩展对象区域。为了补充非区分性区域，在贝叶斯框架下考虑显着性图以优化目标区域。然后在自顶向下的步骤中，将细化对象区域用作监督来训练分割网络并预测对象遮罩。这些对象遮罩提供更准确的本地化并包含更多对象区域。此外，我们将这些对象遮罩作为初始定位，并从中挖掘它们的共同对象特征。迭代地执行这些过程以逐步产生精细的对象掩模并优化分割网络。 Pascal VOC 2012数据集上的实验结果表明，所提出的方法大大优于先前的最先进方法。

##### URL
[http://arxiv.org/abs/1806.04659](http://arxiv.org/abs/1806.04659)

##### PDF
[http://arxiv.org/pdf/1806.04659](http://arxiv.org/pdf/1806.04659)

