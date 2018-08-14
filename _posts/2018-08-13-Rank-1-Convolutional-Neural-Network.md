---
layout: post
title: "Rank-1 Convolutional Neural Network"
date: 2018-08-13 15:55:41
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Hyein Kim, Jungho Yoon, Byeongseon Jeong, Sukho Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a convolutional neural network(CNN) with 3-D rank-1 filters which are composed by the outer product of 1-D filters. After being trained, the 3-D rank-1 filters can be decomposed into 1-D filters in the test time for fast inference. The reason that we train 3-D rank-1 filters in the training stage instead of consecutive 1-D filters is that a better gradient flow can be obtained with this setting, which makes the training possible even in the case where the network with consecutive 1-D filters cannot be trained. The 3-D rank-1 filters are updated by both the gradient flow and the outer product of the 1-D filters in every epoch, where the gradient flow tries to obtain a solution which minimizes the loss function, while the outer product operation tries to make the parameters of the filter to live on a rank-1 sub-space. Furthermore, we show that the convolution with the rank-1 filters results in low rank outputs, constraining the final output of the CNN also to live on a low dimensional subspace.

##### Abstract (translated by Google)
在本文中，我们提出了一个具有3-D秩-1滤波器的卷积神经网络（CNN），它由1-D滤波器的外积组成。在训练之后，可以在测试时间内将3-D秩-1滤波器分解为1-D滤波器以进行快速推理。我们在训练阶段而不是连续的1-D滤波器中训练3-D rank-1滤波器的原因是，使用此设置可以获得更好的梯度流，这使得即使在连续网络的情况下也可以进行训练无法训练1-D滤波器。 3-D rank-1滤波器在每个时期由梯度流和1-D滤波器的外积进行更新，其中梯度流试图获得最小化损失函数的解，而外积运算尝试使过滤器的参数生活在rank-1子空间上。此外，我们证明了使用秩-1滤波器的卷积导致低秩输出，限制CNN的最终输出也生活在低维子空间上。

##### URL
[http://arxiv.org/abs/1808.04303](http://arxiv.org/abs/1808.04303)

##### PDF
[http://arxiv.org/pdf/1808.04303](http://arxiv.org/pdf/1808.04303)

