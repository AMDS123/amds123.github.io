---
layout: post
title: "Semantic Instance Segmentation with a Discriminative Loss Function"
date: 2017-08-08 16:32:48
categories: arXiv_CV
tags: arXiv_CV Semantic_Instance_Segmentation Segmentation CNN
author: Bert De Brabandere, Davy Neven, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic instance segmentation remains a challenging task. In this work we propose to tackle the problem with a discriminative loss function, operating at the pixel level, that encourages a convolutional network to produce a representation of the image that can easily be clustered into instances with a simple post-processing step. The loss function encourages the network to map each pixel to a point in feature space so that pixels belonging to the same instance lie close together while different instances are separated by a wide margin. Our approach of combining an off-the-shelf network with a principled loss function inspired by a metric learning objective is conceptually simple and distinct from recent efforts in instance segmentation. In contrast to previous works, our method does not rely on object proposals or recurrent mechanisms. A key contribution of our work is to demonstrate that such a simple setup without bells and whistles is effective and can perform on par with more complex methods. Moreover, we show that it does not suffer from some of the limitations of the popular detect-and-segment approaches. We achieve competitive performance on the Cityscapes and CVPPP leaf segmentation benchmarks.

##### Abstract (translated by Google)
语义实例分割仍然是一项艰巨的任务。在这项工作中，我们建议用像素级别的差别损失函数来解决这个问题，该算法鼓励卷积网络产生图像的表示，通过简单的后处理步骤可以很容易地将图像聚类成实例。损失函数鼓励网络将每个像素映射到特征空间中的点，使得属于相同实例的像素靠得很近，而不同的实例间隔很大。我们将现成的网络与受指标学习目标启发的原则性损失函数相结合的方法在概念上是简单的并且与最近在实例分割方面的努力截然不同。与之前的作品相比，我们的方法不依赖于对象建议或反复的机制。我们工作的一个主要贡献是证明这样一个没有花里胡哨的简单设置是有效的，并且可以与更复杂的方法相提并论。而且，我们证明它不受流行的检测和分段方法的一些限制。我们在Cityscapes和CVPPP叶子分段基准上获得了有竞争力的表现。

##### URL
[https://arxiv.org/abs/1708.02551](https://arxiv.org/abs/1708.02551)

##### PDF
[https://arxiv.org/pdf/1708.02551](https://arxiv.org/pdf/1708.02551)

