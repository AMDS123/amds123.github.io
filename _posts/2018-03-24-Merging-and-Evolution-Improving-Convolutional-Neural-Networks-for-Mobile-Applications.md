---
layout: post
title: "Merging and Evolution: Improving Convolutional Neural Networks for Mobile Applications"
date: 2018-03-24 15:37:49
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Zheng Qin, Zhaoning Zhang, Shiqing Zhang, Hao Yu, Yuxing Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Compact neural networks are inclined to exploit "sparsely-connected" convolutions such as depthwise convolution and group convolution for employment in mobile applications. Compared with standard "fully-connected" convolutions, these convolutions are more computationally economical. However, "sparsely-connected" convolutions block the inter-group information exchange, which induces severe performance degradation. To address this issue, we present two novel operations named merging and evolution to leverage the inter-group information. Our key idea is encoding the inter-group information with a narrow feature map, then combining the generated features with the original network for better representation. Taking advantage of the proposed operations, we then introduce the Merging-and-Evolution (ME) module, an architectural unit specifically designed for compact networks. Finally, we propose a family of compact neural networks called MENet based on ME modules. Extensive experiments on ILSVRC 2012 dataset and PASCAL VOC 2007 dataset demonstrate that MENet consistently outperforms other state-of-the-art compact networks under different computational budgets. For instance, under the computational budget of 140 MFLOPs, MENet surpasses ShuffleNet by 1% and MobileNet by 1.95% on ILSVRC 2012 top-1 accuracy, while by 2.3% and 4.1% on PASCAL VOC 2007 mAP, respectively.

##### Abstract (translated by Google)
紧凑型神经网络倾向于利用“稀疏连接”的卷积，例如深度卷积和群卷积以用于移动应用。与标准的“完全连接”卷积相比，这些卷积在计算上更经济。然而，“稀疏连接”的卷积会阻止组间信息交换，从而导致严重的性能下降。为了解决这个问题，我们提出了两个新的操作，称为合并和演化，以利用组间信息。我们的主要想法是使用窄特征图对组间信息进行编码，然后将生成的特征与原始网络组合以获得更好的表示。利用所提议的操作，我们将介绍合并与演化（ME）模块，这是一种专门为紧凑型网络设计的架构单元。最后，我们提出了一个基于ME模块的称为MENet的紧凑型神经网络系列。在ILSVRC 2012数据集和PASCAL VOC 2007数据集上的大量实验表明，在不同的计算预算下，MENet始终优于其他最先进的紧凑型网络。例如，在140个MFLOPs的计算预算下，MENet在ILSVRC 2012 top-1精度上分别超过ShuffleNet 1％和MobileNet 1.95％，而PASCAL VOC 2007 mAP分别高出2.3％和4.1％。

##### URL
[https://arxiv.org/abs/1803.09127](https://arxiv.org/abs/1803.09127)

##### PDF
[https://arxiv.org/pdf/1803.09127](https://arxiv.org/pdf/1803.09127)

