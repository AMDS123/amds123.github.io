---
layout: post
title: "Revisiting Single Image Depth Estimation: Toward Higher Resolution Maps with Accurate Object Boundaries"
date: 2018-03-23 07:16:33
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Junjie Hu, Mete Ozay, Yan Zhang, Takayuki Okatani
mathjax: true
---

* content
{:toc}

##### Abstract
We revisit the problem of estimating depth of a scene from its single RGB image. Despite the recent success of deep learning based methods, we show that there is still room for improvement in two aspects by training a deep network consisting of two sub-networks; a base network for providing an initial depth estimate, and a refinement network for refining it. First, spatial resolution of the estimated depth maps can be improved using skip connections among the sub-networks which are trained in a sequential fashion. Second, we can improve estimation accuracy of boundaries of objects in scenes by employing the proposed loss functions using depth gradients. Experimental results show that the proposed network and methods improve depth estimation performance of baseline networks, particularly for reconstruction of small objects and refinement of distortion of edges, and outperform the state-of-the-art methods on benchmark datasets.

##### Abstract (translated by Google)
我们重新讨论从单个RGB图像估计场景深度的问题。尽管近期深度学习方法取得了成功，但我们表明，通过训练由两个子网络组成的深层网络，在两个方面仍有改进的空间;用于提供初始深度估计的基础网络，以及用于提炼它的精化网络。首先，可以使用以顺序方式训练的子网络之间的跳跃连接来改进估计的深度图的空间分辨率。其次，我们可以通过使用建议的使用深度梯度的损失函数来提高场景中物体边界的估计精度。实验结果表明，所提出的网络和方法提高了基线网络的深度估计性能，特别是对于小物体的重建和边缘失真的细化，并且优于基准数据集上的最新方法。

##### URL
[https://arxiv.org/abs/1803.08673](https://arxiv.org/abs/1803.08673)

##### PDF
[https://arxiv.org/pdf/1803.08673](https://arxiv.org/pdf/1803.08673)

