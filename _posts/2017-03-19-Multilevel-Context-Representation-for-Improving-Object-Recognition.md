---
layout: post
title: "Multilevel Context Representation for Improving Object Recognition"
date: 2017-03-19 09:52:28
categories: arXiv_CV
tags: arXiv_CV CNN Classification Recognition
author: Andreas Kölsch, Muhammad Zeshan Afzal, Marcus Liwicki
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose the combined usage of low- and high-level blocks of convolutional neural networks (CNNs) for improving object recognition. While recent research focused on either propagating the context from all layers, e.g. ResNet, (including the very low-level layers) or having multiple loss layers (e.g. GoogLeNet), the importance of the features close to the higher layers is ignored. This paper postulates that the use of context closer to the high-level layers provides the scale and translation invariance and works better than using the top layer only. In particular, we extend AlexNet and GoogLeNet by additional connections in the top $n$ layers. In order to demonstrate the effectiveness of the proposed approach, we evaluated it on the standard ImageNet task. The relative reduction of the classification error is around 1-2% without affecting the computational cost. Furthermore, we show that this approach is orthogonal to typical test data augmentation techniques, as recently introduced by Szegedy et al. (leading to a runtime reduction of 144 during test time).

##### Abstract (translated by Google)
在这项工作中，我们提出了用于改善目标识别的低层和高层卷积神经网络（CNN）的组合使用。尽管最近的研究集中于从所有层传播环境，例如ResNet（包括非常低层）或者具有多个丢失层（例如，GoogLeNet），忽略了靠近较高层的特征的重要性。本文假定，使用更接近高层的上下文提供了比例和平移不变性，并且比只使用顶层更好。特别是，我们通过额外的$ n $层上的连接来扩展AlexNet和GoogLeNet。为了证明所提出方法的有效性，我们在标准ImageNet任务上评估了它。分类错误的相对减少约为1-2％而不影响计算成本。此外，我们表明，这种方法正交于典型的测试数据增强技术，最近由塞格德等人介绍。 （导致在测试期间运行时间减少了144）。

##### URL
[https://arxiv.org/abs/1703.06408](https://arxiv.org/abs/1703.06408)

##### PDF
[https://arxiv.org/pdf/1703.06408](https://arxiv.org/pdf/1703.06408)

