---
layout: post
title: "Learning Short-Cut Connections for Object Counting"
date: 2018-05-08 09:31:51
categories: arXiv_CV
tags: arXiv_CV CNN
author: Daniel Oñoro-Rubio, Mathias Niepert, Roberto J. López-Sastre
mathjax: true
---

* content
{:toc}

##### Abstract
Object counting is an important task in computer vision due to its growing demand in applications such as traffic monitoring or surveillance. In this paper, we consider object counting as a learning problem of a joint feature extraction and pixel-wise object density estimation with Convolutional-Deconvolutional networks. We propose a novel counting model, named Gated U-Net (GU-Net). Specifically, we propose to enrich the U-Net architecture with the concept of learnable short-cut connections. Standard short-cut connections are connections between layers in deep neural networks which skip at least one intermediate layer. Instead of simply setting short-cut connections, we propose to learn these connections from data. Therefore, our short-cut can work as a gating unit, which optimizes the flow of information between convolutional and deconvolutional layers in the U-Net architecture. We evaluate the proposed GU-Net architecture on three commonly used benchmark data sets for object counting. GU-Nets consistently outperform the base U-Net architecture, and achieve state-of-the-art performance.

##### Abstract (translated by Google)
由于对交通监控或监控等应用的需求日益增长，因此物体计数是计算机视觉领域的一项重要任务。在本文中，我们将对象计数视为卷积去卷积网络的联合特征提取和像素级对象密度估计的学习问题。我们提出了一种新颖的计数模型，名为Gated U-Net（GU-Net）。具体而言，我们建议以可学习的快捷连接的概念丰富U-Net架构。标准的快捷连接是深层神经网络中的层之间的连接，其跳过至少一个中间层。我们建议从数据中学习这些连接，而不是简单地设置快捷连接。因此，我们的捷径可以作为一个门控单元，它可以优化U-Net架构中卷积和反卷积层之间的信息流。我们在三个常用的基准数据集上评估提议的GU-Net体系结构以进行对象计数。 GU-Nets始终超越基础U-Net架构，并实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1805.02919](https://arxiv.org/abs/1805.02919)

##### PDF
[https://arxiv.org/pdf/1805.02919](https://arxiv.org/pdf/1805.02919)

