---
layout: post
title: "A Simple Riemannian Manifold Network for Image Set Classification"
date: 2018-05-27 14:05:47
categories: arXiv_CV
tags: arXiv_CV Face Classification Deep_Learning Recognition Face_Recognition
author: Rui Wang, Xiao-Jun Wu, Josef Kittler
mathjax: true
---

* content
{:toc}

##### Abstract
In the domain of image-set based classification, a considerable advance has been made by representing original image sets as covariance matrices which typical lie in a Riemannian manifold. Specifically, it is a Symmetric Positive Definite (SPD) manifold. Traditional manifold learning methods inevitably have the property of high computational complexity or weak performance of the feature representation. In order to overcome these limitations, we propose a very simple Riemannian manifold network for image set classification. Inspired by deep learning architectures, we design a fully connected layer to generate more novel, more powerful SPD matrices. However we exploit the rectifying layer to prevent the input SPD matrices from being singular. We also introduce a non-linear learning of the proposed network with an innovative objective function. Furthermore we devise a pooling layer to further reduce the redundancy of the input SPD matrices, and the log-map layer to project the SPD manifold to the Euclidean space. For learning the connection weights between the input layer and the fully connected layer, we use Two-directional two-dimensional Principal Component Analysis ((2D)2PCA) algorithm. The proposed Riemannian manifold network (RieMNet) avoids complex computing and can be built and trained extremely easy and efficient. We have also developed a deep version of RieMNet, named as DRieMNet. The proposed RieMNet and DRieMNet are evaluated on three tasks: video-based face recognition, set-based object categorization, and set-based cell identification. Extensive experimental results show the superiority of our method over the state-of-the-art.

##### Abstract (translated by Google)
在基于图像集的分类领域，通过将原始图像集表示为典型位于黎曼流形中的协方差矩阵已经取得了相当大的进步。具体而言，它是一个对称正定（SPD）流形。传统的流形学习方法不可避免地具有计算复杂度高或特征表示性能差的特点。为了克服这些限制，我们提出了一个非常简单的黎曼流形网络用于图像集分类。受深度学习架构的启发，我们设计了一个完全连接的层来生成更新颖，更强大的SPD矩阵。然而，我们利用整流层防止输入SPD矩阵为单数。我们还引入了具有创新目标函数的提议网络的非线性学习。此外，我们设计了一个池化层来进一步减少输入SPD矩阵的冗余度，以及用于将SPD流形投影到欧几里德空间的对数图层。为了学习输入层和完全连接层之间的连接权重，我们使用了双向二维主成分分析（（2D）2PCA）算法。所提出的黎曼流形网络（RieMNet）避免了复杂的计算，并且可以非常容易且高效地构建和训练。我们还开发了深度版RieMNet，名为DRieMNet。建议的RieMNet和DRieMNet在三项任务中进行评估：基于视频的人脸识别，基于集合的对象分类和基于集合的小区识别。广泛的实验结果表明我们的方法优于最先进的技术。

##### URL
[http://arxiv.org/abs/1805.10628](http://arxiv.org/abs/1805.10628)

##### PDF
[http://arxiv.org/pdf/1805.10628](http://arxiv.org/pdf/1805.10628)

