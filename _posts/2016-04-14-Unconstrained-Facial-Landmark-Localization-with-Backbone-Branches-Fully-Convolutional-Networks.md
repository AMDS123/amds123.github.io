---
layout: post
title: "Unconstrained Facial Landmark Localization with Backbone-Branches Fully-Convolutional Networks"
date: 2016-04-14 07:38:52
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference
author: Zhujin Liang, Shengyong Ding, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates how to rapidly and accurately localize facial landmarks in unconstrained, cluttered environments rather than in the well segmented face images. We present a novel Backbone-Branches Fully-Convolutional Neural Network (BB-FCN), which produces facial landmark response maps directly from raw images without relying on pre-process or sliding window approaches. BB-FCN contains one backbone and a number of network branches with each corresponding to one landmark type, and it operates in a progressive manner. Specifically, the backbone roughly detects the locations of facial landmarks by taking the whole image as input, and the branches further refine the localizations based on a local observation from the backbone's intermediate feature map. Moreover, our backbone-branches architecture does not contain full-connection layers for location regression, leading to efficient learning and inference. Our extensive experiments show that our model achieves superior performances over other state-of-the-arts under both the constrained (i.e. with face regions) and the "in the wild" scenarios.

##### Abstract (translated by Google)
本文研究如何快速和准确地定位在不受约束的杂乱环境中的面部标志，而不是在良好分割的面部图像中。我们提出了一种新的骨干分支全卷积神经网络（BB-FCN），它直接从原始图像生成面部标志响应图，而不依赖于预处理或滑动窗口方法。 BB-FCN包含一个骨干和多个网络分支，每个网络分支对应一个地标类型，并且以渐进方式运行。具体来说，骨干通过将整个图像作为输入来粗略地检测面部标志的位置，并且分支进一步根据骨干的中间特征图的局部观察来细化面部定位。此外，我们的骨干分支架构不包含位置回归的全连接层，导致高效的学习和推理。我们广泛的实验表明，我们的模型在约束（即与面部区域）和“在野外”场景下都比其他艺术水平获得了更好的表现。

##### URL
[https://arxiv.org/abs/1507.03409](https://arxiv.org/abs/1507.03409)

##### PDF
[https://arxiv.org/e-print/1507.03409](https://arxiv.org/e-print/1507.03409)

