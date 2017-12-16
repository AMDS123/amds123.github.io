---
layout: post
title: "Transfer Learning in CNNs Using Filter-Trees"
date: 2017-11-27 12:29:44
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Recognition
author: Suresh Kirthi Kumaraswamy, PS Sastry, KR Ramakrishnan
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) are very effective for many pattern recognition tasks. However, training deep CNNs needs extensive computation and large training data. In this paper we propose Bank of Filter-Trees (BFT) as a trans- fer learning mechanism for improving efficiency of learning CNNs. A filter-tree corresponding to a filter in k^{th} convolu- tional layer of a CNN is a subnetwork consisting of the filter along with all its connections to filters in all preceding layers. An ensemble of such filter-trees created from the k^{th} layers of many CNNs learnt on different but related tasks, forms the BFT. To learn a new CNN, we sample from the BFT to select a set of filter trees. This fixes the target net up to the k th layer and only the remaining network would be learnt using train- ing data of new task. Through simulations we demonstrate the effectiveness of this idea of BFT. This method constitutes a novel transfer learning technique where transfer is at a sub- network level; transfer can be effected from multiple source networks; and, with no finetuning of the transferred weights, the performance achieved is on par with networks that are trained from scratch.

##### Abstract (translated by Google)
卷积神经网络（CNN）对于许多模式识别任务是非常有效的。但是，深度CNN训练需要大量的计算和大量的训练数据。在本文中，我们提出过滤树（BFT）作为提高学习CNN效率的转换学习机制。与CNN的第k个卷积层中的滤波器相对应的滤波器树是由滤波器以及其所有连接到滤波器的所有前面的层组成的子网络。从许多CNN的第k层创建的这样的滤波器树的集合形成了BFT。为了学习一个新的CNN，我们从BFT中选取一组过滤树。这将目标网络固定到第k层，并且仅使用新任务的训练数据来学习剩余的网络。通过仿真，我们证明了BFT的这种思想的有效性。这种方法构成了一种新的转移学习技术，其中转移处于子网络级别;可以从多个源网络进行传输;而且在不调整权重的情况下，所获得的性能与从头开始训练的网络相当。

##### URL
[https://arxiv.org/abs/1711.09648](https://arxiv.org/abs/1711.09648)

##### PDF
[https://arxiv.org/pdf/1711.09648](https://arxiv.org/pdf/1711.09648)

