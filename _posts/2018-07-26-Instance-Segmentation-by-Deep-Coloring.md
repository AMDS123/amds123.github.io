---
layout: post
title: "Instance Segmentation by Deep Coloring"
date: 2018-07-26 08:20:15
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Victor Kulikov, Victor Yurchenko, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new and, arguably, a very simple reduction of instance segmentation to semantic segmentation. This reduction allows to train feed-forward non-recurrent deep instance segmentation systems in an end-to-end fashion using architectures that have been proposed for semantic segmentation. Our approach proceeds by introducing a fixed number of labels (colors) and then dynamically assigning object instances to those labels during training (coloring). A standard semantic segmentation objective is then used to train a network that can color previously unseen images. At test time, individual object instances can be recovered from the output of the trained convolutional network using simple connected component analysis. In the experimental validation, the coloring approach is shown to be capable of solving diverse instance segmentation tasks arising in autonomous driving (the Cityscapes benchmark), plant phenotyping (the CVPPP leaf segmentation challenge), and high-throughput microscopy image analysis. 
 The source code is publicly available: https://github.com/kulikovv/DeepColoring.

##### Abstract (translated by Google)
我们提出了一种新的，可以说是非常简单的将实例分割简化为语义分割。这种减少允许使用已经提出用于语义分割的架构以端到端的方式训练前馈非循环深度实例分割系统。我们的方法是通过引入固定数量的标签（颜色），然后在训练（着色）期间动态地将对象实例分配给这些标签。然后使用标准语义分割目标来训练可以对先前看不见的图像着色的网络。在测试时，可以使用简单的连通分量分析从训练的卷积网络的输出中恢复单个对象实例。在实验验证中，着色方法显示能够解决在自动驾驶（城市景观基准），植物表型分析（CVPPP叶片分割挑战）和高通量显微镜图像分析中出现的各种实例分割任务。
 源代码可公开获取：https：//github.com/kulikovv/DeepColoring。

##### URL
[http://arxiv.org/abs/1807.10007](http://arxiv.org/abs/1807.10007)

##### PDF
[http://arxiv.org/pdf/1807.10007](http://arxiv.org/pdf/1807.10007)

