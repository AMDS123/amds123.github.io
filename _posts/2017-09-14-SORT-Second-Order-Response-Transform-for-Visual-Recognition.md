---
layout: post
title: "SORT: Second-Order Response Transform for Visual Recognition"
date: 2017-09-14 13:25:00
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Yan Wang, Lingxi Xie, Chenxi Liu, Ya Zhang, Wenjun Zhang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we reveal the importance and benefits of introducing second-order operations into deep neural networks. We propose a novel approach named Second-Order Response Transform (SORT), which appends element-wise product transform to the linear sum of a two-branch network module. A direct advantage of SORT is to facilitate cross-branch response propagation, so that each branch can update its weights based on the current status of the other branch. Moreover, SORT augments the family of transform operations and increases the nonlinearity of the network, making it possible to learn flexible functions to fit the complicated distribution of feature space. SORT can be applied to a wide range of network architectures, including a branched variant of a chain-styled network and a residual network, with very light-weighted modifications. We observe consistent accuracy gain on both small (CIFAR10, CIFAR100 and SVHN) and big (ILSVRC2012) datasets. In addition, SORT is very efficient, as the extra computation overhead is less than 5%.

##### Abstract (translated by Google)
在本文中，我们揭示了在深度神经网络中引入二阶运算的重要性和好处。我们提出了一种名为二阶响应变换（SORT）的新方法，它将元素明智的乘积变换附加到双分支网络模块的线性和上。 SORT的一个直接优势是便于跨分支响应传播，以便每个分支可以根据另一个分支的当前状态更新其权重。此外，SORT增强了变换操作族，增加了网络的非线性，使学习灵活的函数成为可能，以适应复杂的特征空间分布。 SORT可以应用于广泛的网络体系结构，包括链式网络和残余网络的分支变体，并且具有非常轻的权重修改。我们观察到小（CIFAR10，CIFAR100和SVHN）和大（ILSVRC2012）数据集一致的准确性增益。另外，SORT是非常有效的，因为额外的计算开销小于5％。

##### URL
[https://arxiv.org/abs/1703.06993](https://arxiv.org/abs/1703.06993)

##### PDF
[https://arxiv.org/pdf/1703.06993](https://arxiv.org/pdf/1703.06993)

