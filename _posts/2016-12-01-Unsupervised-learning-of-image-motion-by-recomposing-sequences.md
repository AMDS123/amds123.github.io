---
layout: post
title: "Unsupervised learning of image motion by recomposing sequences"
date: 2016-12-01 21:18:45
categories: arXiv_CV
tags: arXiv_CV Tracking Embedding RNN
author: Andrew Jaegle, Stephen Phillips, Daphne Ippolito, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method for learning a representation of image motion in an unsupervised fashion. We do so by learning an image sequence embedding that respects associativity and invertibility properties of composed sequences with known temporal order. This procedure makes minimal assumptions about scene content, and the resulting networks learn to exploit rigid and non-rigid motion cues. We show that a deep neural network trained to respect these constraints implicitly identifies the characteristic motion patterns of many different sequence types. Our network architecture consists of a CNN followed by an LSTM and is structured to learn motion representations over sequences of arbitrary length. We demonstrate that a network trained using our unsupervised procedure on real-world sequences of human actions and vehicle motion can capture semantic regions corresponding to the motion in the scene, and not merely image-level differences, without requiring any motion labels. Furthermore, we present results that suggest our method can be used to extract information useful for independent motion tracking, localization, and nearest neighbor identification. Our results suggest that this representation may be useful for motion-related tasks where explicit labels are often very difficult to obtain.

##### Abstract (translated by Google)
我们提出了一种以无监督的方式学习图像运动表示的新方法。我们通过学习一个图像序列嵌入的方法来实现这一点，该序列嵌入考虑了已知时间顺序的组合序列的相关性和可逆性。这个过程对场景内容做了最少的假设，最终的网络学习利用刚性和非刚性的运动线索。我们表明，深度神经网络训练，尊重这些约束隐式确定了许多不同序列类型的特征运动模式。我们的网络架构由一个CNN和一个LSTM组成，可以学习任意长度序列的运动表示。我们证明，使用我们的无监督程序在人类行为和车辆运动的真实世界序列上训练的网络可以捕捉与场景中的运动相对应的语义区域，而不需要图像级差异，而​​不需要任何运动标签。此外，我们目前的结果表明，我们的方法可以用来提取有用的独立运动跟踪，本地化和最近邻居识别信息。我们的研究结果表明，这种表示可能是有用的运动相关的任务，显式标签通常很难获得。

##### URL
[https://arxiv.org/abs/1612.00472](https://arxiv.org/abs/1612.00472)

##### PDF
[https://arxiv.org/pdf/1612.00472](https://arxiv.org/pdf/1612.00472)

