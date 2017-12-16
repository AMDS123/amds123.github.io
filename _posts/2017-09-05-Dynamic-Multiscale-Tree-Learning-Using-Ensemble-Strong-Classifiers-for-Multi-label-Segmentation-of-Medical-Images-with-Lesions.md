---
layout: post
title: "Dynamic Multiscale Tree Learning Using Ensemble Strong Classifiers for Multi-label Segmentation of Medical Images with Lesions"
date: 2017-09-05 21:41:58
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Classification
author: Samya Amiri, Mohamed Ali Mahjoub, Islem Rekik
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a dynamic multiscale tree (DMT) architecture that learns how to leverage the strengths of different existing classifiers for supervised multi-label image segmentation. Unlike previous works that simply aggregate or cascade classifiers for addressing image segmentation and labeling tasks, we propose to embed strong classifiers into a tree structure that allows bi-directional flow of information between its classifier nodes to gradually improve their performances. Our DMT is a generic classification model that inherently embeds different cascades of classifiers while enhancing learning transfer between them to boost up their classification accuracies. Specifically, each node in our DMT can nest a Structured Random Forest (SRF) classifier or a Bayesian Network (BN) classifier. The proposed SRF-BN DMT architecture has several appealing properties. First, while SRF operates at a patch-level (regular image region), BN operates at the super-pixel level (irregular image region), thereby enabling the DMT to integrate multi-level image knowledge in the learning process. Second, although BN is powerful in modeling dependencies between image elements (superpixels, edges) and their features, the learning of its structure and parameters is challenging. On the other hand, SRF may fail to accurately detect very irregular object boundaries. The proposed DMT robustly overcomes these limitations for both classifiers through the ascending and descending flow of contextual information between each parent node and its children nodes. Third, we train DMT using different scales, where we progressively decrease the patch and superpixel sizes as we go deeper along the tree edges nearing its leaf nodes. Last, DMT demonstrates its outperformance in comparison to several state-of-the-art segmentation methods for multi-labeling of brain images with gliomas.

##### Abstract (translated by Google)
我们介绍一个动态多尺度树（DMT）架构，学习如何利用不同的现有分类器的强度监督多标签图像分割。不同于以前的工作，简单地聚合或级联分类器来解决图像分割和标记任务，我们建议将强分类器嵌入树结构，允许其分类器节点之间的信息双向流动，以逐步提高其性能。我们的DMT是一个通用的分类模型，它固有地嵌入不同的分类器级联，同时增强它们之间的学习转移以提高它们的分类准确性。具体而言，我们的DMT中的每个节点可以嵌套结构化随机森林（SRF）分类器或贝叶斯网络（BN）分类器。所提出的SRF-BN DMT体系结构具有几个吸引人的特性。首先，当SRF以补丁级别（规则图像区域）操作时，BN在超像素级别（不规则图像区域）操作，从而使DMT能够将多级图像知识集成到学习过程中。其次，尽管BN在图像元素（超像素，边缘）与其特征之间建模依赖关系方面功能强大，但其结构和参数的学习是具有挑战性的。另一方面，SRF可能无法准确检测到非常不规则的物体边界。所提出的DMT通过每个父节点与其子节点之间的上下文信息的上升和下降流来强健地克服这两个分类器的这些限制。第三，我们使用不同的尺度来训练DMT，随着我们沿着靠近叶节点的树边缘深入地逐渐减小贴片和超像素尺寸。最后，与用于胶质瘤的大脑图像的多标记的几种最先进的分割方法相比，DMT显示其优越性。

##### URL
[https://arxiv.org/abs/1709.01602](https://arxiv.org/abs/1709.01602)

##### PDF
[https://arxiv.org/pdf/1709.01602](https://arxiv.org/pdf/1709.01602)

