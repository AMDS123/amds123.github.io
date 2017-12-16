---
layout: post
title: "Orthogonal and Idempotent Transformations for Learning Deep Neural Networks"
date: 2017-07-19 08:35:10
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jingdong Wang, Yajie Xing, Kexin Zhang, Cha Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Identity transformations, used as skip-connections in residual networks, directly connect convolutional layers close to the input and those close to the output in deep neural networks, improving information flow and thus easing the training. In this paper, we introduce two alternative linear transforms, orthogonal transformation and idempotent transformation. According to the definition and property of orthogonal and idempotent matrices, the product of multiple orthogonal (same idempotent) matrices, used to form linear transformations, is equal to a single orthogonal (idempotent) matrix, resulting in that information flow is improved and the training is eased. One interesting point is that the success essentially stems from feature reuse and gradient reuse in forward and backward propagation for maintaining the information during flow and eliminating the gradient vanishing problem because of the express way through skip-connections. We empirically demonstrate the effectiveness of the proposed two transformations: similar performance in single-branch networks and even superior in multi-branch networks in comparison to identity transformations.

##### Abstract (translated by Google)
身份转换作为残余网络中的跳过连接，直接连接靠近输入的卷积层以及深度神经网络中靠近输出的卷积层，从而改善信息流，从而减轻训练负担。在本文中，我们介绍两种可选的线性变换，正交变换和幂等变换。根据正交和幂等矩阵的定义和性质，用于形成线性变换的多个正交（相同幂等）矩阵的乘积等于单个正交（幂等）矩阵，导致信息流被改进，训练被缓解。一个有趣的地方在于，成功本质上来自前向和后向传播中的特征重用和梯度重用，以便在流程中维护信息并消除由于跳过连接的高速方式而导致的梯度消失问题。我们经验性地证明了所提出的两种转换的有效性：单分支网络中的相似性能，以及与身份转换相比在多分支网络中甚至更优。

##### URL
[https://arxiv.org/abs/1707.05974](https://arxiv.org/abs/1707.05974)

##### PDF
[https://arxiv.org/pdf/1707.05974](https://arxiv.org/pdf/1707.05974)

