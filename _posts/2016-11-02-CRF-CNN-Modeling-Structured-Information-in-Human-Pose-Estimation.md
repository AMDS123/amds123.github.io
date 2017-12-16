---
layout: post
title: "CRF-CNN: Modeling Structured Information in Human Pose Estimation"
date: 2016-11-02 04:42:40
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Xiao Chu, Wanli Ouyang, Hongsheng Li, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNN) have achieved great success. On the other hand, modeling structural information has been proved critical in many vision problems. It is of great interest to integrate them effectively. In a classical neural network, there is no message passing between neurons in the same layer. In this paper, we propose a CRF-CNN framework which can simultaneously model structural information in both output and hidden feature layers in a probabilistic way, and it is applied to human pose estimation. A message passing scheme is proposed, so that in various layers each body joint receives messages from all the others in an efficient way. Such message passing can be implemented with convolution between features maps in the same layer, and it is also integrated with feedforward propagation in neural networks. Finally, a neural network implementation of end-to-end learning CRF-CNN is provided. Its effectiveness is demonstrated through experiments on two benchmark datasets.

##### Abstract (translated by Google)
深卷积神经网络（CNN）取得了巨大的成功。另一方面，建模结构信息已被证明是许多视觉问题的关键。有效地整合它们是非常有意义的。在经典的神经网络中，在同一层中的神经元之间没有消息传递。本文提出了一种CRF-CNN框架，该框架能够以概率的方式同时对输出和隐藏要素层的结构信息进行建模，并将其应用于人体姿态估计。提出了一种消息传递方案，以便在各个层面上，各个身体联合以有效的方式接收来自所有其他人的消息。这种消息传递可以通过在同一图层中的特征映射之间的卷积来实现，并且还与神经网络中的前馈传播相结合。最后，提供了端到端学习CRF-CNN的神经网络实现。通过对两个基准数据集的实验来证明其有效性。

##### URL
[https://arxiv.org/abs/1611.00468](https://arxiv.org/abs/1611.00468)

##### PDF
[https://arxiv.org/pdf/1611.00468](https://arxiv.org/pdf/1611.00468)

