---
layout: post
title: "Is the deconvolution layer the same as a convolutional layer?"
date: 2016-09-22 15:11:11
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Wenzhe Shi, Jose Caballero, Lucas Theis, Ferenc Huszar, Andrew Aitken, Christian Ledig, Zehan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this note, we want to focus on aspects related to two questions most people asked us at CVPR about the network we presented. Firstly, What is the relationship between our proposed layer and the deconvolution layer? And secondly, why are convolutions in low-resolution (LR) space a better choice? These are key questions we tried to answer in the paper, but we were not able to go into as much depth and clarity as we would have liked in the space allowance. To better answer these questions in this note, we first discuss the relationships between the deconvolution layer in the forms of the transposed convolution layer, the sub-pixel convolutional layer and our efficient sub-pixel convolutional layer. We will refer to our efficient sub-pixel convolutional layer as a convolutional layer in LR space to distinguish it from the common sub-pixel convolutional layer. We will then show that for a fixed computational budget and complexity, a network with convolutions exclusively in LR space has more representation power at the same speed than a network that first upsamples the input in high resolution space.

##### Abstract (translated by Google)
在这个笔记中，我们想把重点放在与大多数人在CVPR上提出的关于我们提供的网络的两个问题有关的方面。首先，我们提出的层和去卷积层之间的关系是什么？其次，为什么低分辨率（LR）空间中的卷积是一个更好的选择？这些是我们在论文中试图回答的关键问题，但是我们没有能够像太空津贴那样深入和透彻地进行讨论。为了更好地回答这个问题，我们首先讨论转置卷积层，亚像素卷积层和我们有效的亚像素卷积层形式的解卷积层之间的关系。我们将把我们有效的子像素卷积层作为LR空间中的卷积层来区分它与常见的子像素卷积层。然后，我们将显示，对于固定的计算预算和复杂性，仅在LR空间中卷积的网络具有比在高分辨率空间中首先上采样输入的网络相同的速度的更高的表示能力。

##### URL
[https://arxiv.org/abs/1609.07009](https://arxiv.org/abs/1609.07009)

##### PDF
[https://arxiv.org/pdf/1609.07009](https://arxiv.org/pdf/1609.07009)

