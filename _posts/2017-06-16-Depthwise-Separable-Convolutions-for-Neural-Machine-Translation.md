---
layout: post
title: "Depthwise Separable Convolutions for Neural Machine Translation"
date: 2017-06-16 02:35:48
categories: arXiv_CL
tags: arXiv_CL CNN Image_Classification Classification
author: Lukasz Kaiser, Aidan N. Gomez, Francois Chollet
mathjax: true
---

* content
{:toc}

##### Abstract
Depthwise separable convolutions reduce the number of parameters and computation used in convolutional operations while increasing representational efficiency. They have been shown to be successful in image classification models, both in obtaining better models than previously possible for a given parameter count (the Xception architecture) and considerably reducing the number of parameters required to perform at a given level (the MobileNets family of architectures). Recently, convolutional sequence-to-sequence networks have been applied to machine translation tasks with good results. In this work, we study how depthwise separable convolutions can be applied to neural machine translation. We introduce a new architecture inspired by Xception and ByteNet, called SliceNet, which enables a significant reduction of the parameter count and amount of computation needed to obtain results like ByteNet, and, with a similar parameter count, achieves new state-of-the-art results. In addition to showing that depthwise separable convolutions perform well for machine translation, we investigate the architectural changes that they enable: we observe that thanks to depthwise separability, we can increase the length of convolution windows, removing the need for filter dilation. We also introduce a new "super-separable" convolution operation that further reduces the number of parameters and computational cost for obtaining state-of-the-art results.

##### Abstract (translated by Google)
深度可分卷积减少了卷积运算中使用的参数和计算的数量，同时提高了代表性效率。已经证明，它们在图像分类模型中是成功的，既获得了比以往更可靠的模型（Xception体系结构），又大大减少了在给定级别执行所需的参数数量（MobileNets系列体系结构）。最近，卷积序列网络已被应用于机器翻译任务，效果良好。在这项工作中，我们研究如何深度可分卷积可应用于神经机器翻译。我们引入了一个受Xception和ByteNet启发的新架构，称为SliceNet，它可以显着减少获得像ByteNet这样的结果所需的参数数量和计算量，并且通过类似的参数数量实现新的状态 - 艺术成果。除了展示深度可分离的卷积在机器翻译中表现良好以外，我们还研究了它们所支持的体系结构变化：我们观察到，由于深度可分性，我们可以增加卷积窗口的长度，消除对滤波器膨胀的需要。我们还引入了一个新的“超可分离”卷积运算，进一步减少了获取最新结果的参数数量和计算成本。

##### URL
[https://arxiv.org/abs/1706.03059](https://arxiv.org/abs/1706.03059)

##### PDF
[https://arxiv.org/pdf/1706.03059](https://arxiv.org/pdf/1706.03059)

