---
layout: post
title: "Rain Streak Removal for Single Image via Kernel Guided CNN"
date: 2018-08-26 12:53:18
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Ye-Tao Wang, Xi-Le Zhao, Tai-Xiang Jiang, Ting-Zhu Huang, Liang-Jian Deng, Yi Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Rain streak removal is an important issue and has recently been investigated extensively. Existing methods, especially the newly emerged deep learning methods, could remove the rain streaks well in many cases. However the essential factor in the generative procedure of the rain streaks, i.e., the motion blur, which leads to the line pattern appearances, were neglected by the deep learning rain streaks approaches and this resulted in over-derain or under-derain results. In this paper, we propose a novel rain streak removal approach using a kernel guided convolutional neural network (KGCNN), achieving the state-of-the-art performance with simple network architectures. We first model the rain streak interference with its motion blur mechanism. Then, our framework starts with learning the motion blur kernel, which is determined by two factors including angle and length, by a plain neural network, denoted as parameter net, from a patch of the texture component. Then, after a dimensionality stretching operation, the learned motion blur kernel is stretched into a degradation map with the same spatial size as the rainy patch. The stretched degradation map together with the texture patch is subsequently input into a derain convolutional network, which is a typical ResNet architecture and trained to output the rain streaks with the guidance of the learned motion blur kernel. Experiments conducted on extensive synthetic and real data demonstrate the effectiveness of the proposed method, which preserves the texture and the contrast while removing the rain streaks.

##### Abstract (translated by Google)
雨水排除是一个重要问题，最近已被广泛研究。现有的方法，特别是新出现的深度学习方法，可以在很多情况下很好地消除雨水条纹。然而，雨条纹的生成过程中的基本因素，即导致线条图案出现的运动模糊，被深度学习雨条纹方法所忽略，并且这导致过度消除或欠消失的结果。在本文中，我们提出了一种使用核引导卷积神经网络（KGCNN）的新型雨水排除方法，通过简单的网络架构实现了最先进的性能。我们首先用它的运动模糊机制模拟雨条干扰。然后，我们的框架开始于学习运动模糊核，该核由两个因素（包括角度和长度）由一个普通的神经网络（表示为参数网）从纹理组件的一个片段决定。然后，在维度拉伸操作之后，将学习的运动模糊核拉伸成具有与雨季补丁相同的空间大小的劣化映射。随后将拉伸的劣化映射与纹理补片一起输入到derain卷积网络中，该网络是典型的ResNet架构并且训练为在学习的运动模糊内核的指导下输出雨条纹。在广泛的合成和实际数据上进行的实验证明了所提出的方法的有效性，该方法在去除雨条纹的同时保持纹理和对比度。

##### URL
[http://arxiv.org/abs/1808.08545](http://arxiv.org/abs/1808.08545)

##### PDF
[http://arxiv.org/pdf/1808.08545](http://arxiv.org/pdf/1808.08545)

