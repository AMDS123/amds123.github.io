---
layout: post
title: "Multigrid Neural Architectures"
date: 2017-05-11 19:24:33
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Classification
author: Tsung-Wei Ke, Michael Maire, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a multigrid extension of convolutional neural networks (CNNs). Rather than manipulating representations living on a single spatial grid, our network layers operate across scale space, on a pyramid of grids. They consume multigrid inputs and produce multigrid outputs; convolutional filters themselves have both within-scale and cross-scale extent. This aspect is distinct from simple multiscale designs, which only process the input at different scales. Viewed in terms of information flow, a multigrid network passes messages across a spatial pyramid. As a consequence, receptive field size grows exponentially with depth, facilitating rapid integration of context. Most critically, multigrid structure enables networks to learn internal attention and dynamic routing mechanisms, and use them to accomplish tasks on which modern CNNs fail. Experiments demonstrate wide-ranging performance advantages of multigrid. On CIFAR and ImageNet classification tasks, flipping from a single grid to multigrid within the standard CNN paradigm improves accuracy, while being compute and parameter efficient. Multigrid is independent of other architectural choices; we show synergy in combination with residual connections. Multigrid yields dramatic improvement on a synthetic semantic segmentation dataset. Most strikingly, relatively shallow multigrid networks can learn to directly perform spatial transformation tasks, where, in contrast, current CNNs fail. Together, our results suggest that continuous evolution of features on a multigrid pyramid is a more powerful alternative to existing CNN designs on a flat grid.

##### Abstract (translated by Google)
我们提出卷积神经网络（CNN）的多重网格扩展。生活在一个单一的空间网格上，而不是操纵表示，我们的网络层在一个金字塔的网格上跨越尺度空间运作。它们消耗多重网格输入并产生多重网格输出;卷积滤波器本身具有范围内和跨尺度的范围。这个方面不同于简单的多尺度设计，它只处理不同尺度的输入。从信息流的角度来看，多网格网络通过空间金字塔传递消息。因此，感受野的大小随深度呈指数级增长，促进了情景的快速整合。最重要的是，多重网格结构使网络能够学习内部关注和动态路由机制，并使用它们来完成现代CNN失败的任务。实验证明了多重网格具有广泛的性能优势。在CIFAR和ImageNet分类任务中，在标准CNN范例内从单个网格翻转到多个网格提高了准确性，同时具有计算和参数高效性。多重网格独立于其他架构选择;我们显示协同作用与残余连接相结合。多重网格在合成的语义分割数据集上产生了巨大的改进。最引人注目的是，相对较浅的多网格网络可以学习直接执行空间变换任务，而目前的CNN则失败。总之，我们的研究结果表明，多格金字塔上的特征的不断演变是现有CNN设计在平面网格上的更有力的替代方案。

##### URL
[https://arxiv.org/abs/1611.07661](https://arxiv.org/abs/1611.07661)

##### PDF
[https://arxiv.org/pdf/1611.07661](https://arxiv.org/pdf/1611.07661)

