---
layout: post
title: "LF-Net: Learning Local Features from Images"
date: 2018-05-24 13:42:17
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Yuki Ono, Eduard Trulls, Pascal Fua, Kwang Moo Yi
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel deep architecture and a training strategy to learn a local feature pipeline from scratch, using collections of images without the need for human supervision. To do so we exploit depth and relative camera pose cues to create a virtual target that the network should achieve on one image, provided the outputs of the network for the other image. While this process is inherently non-differentiable, we show that we can optimize the network in a two-branch setup by confining it to one branch, while preserving differentiability in the other. We train our method on both indoor and outdoor datasets, with depth data from 3D sensors for the former, and depth estimates from an off-the-shelf Structure-from-Motion solution for the latter. Our models outperform the state of the art on sparse feature matching on both datasets, while running at 60+ fps for QVGA images.

##### Abstract (translated by Google)
我们提出了一种新颖的深层架构和培训策略，可以从头开始学习局部特征管道，使用图像集合而无需人工监控。为此，我们利用深度和相对位置姿势提示来创建网络应在一个图像上实现的虚拟目标，为其他图像提供网络输出。虽然这个过程本质上是不可区分的，但我们表明，我们可以通过将它限制在一个分支上，并在另一个分支中保留差异性来优化网络。我们在室内和室外数据集上训练我们的方法，前者采用3D传感器的深度数据，后者采用现成的运动结构解决方案进行深度估算。我们的模型在两个数据集上的稀疏特征匹配方面都优于现有技术，而QVGA图像的运行速度为60+ fps。

##### URL
[http://arxiv.org/abs/1805.09662](http://arxiv.org/abs/1805.09662)

##### PDF
[http://arxiv.org/pdf/1805.09662](http://arxiv.org/pdf/1805.09662)

