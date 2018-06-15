---
layout: post
title: "A Flexible Convolutional Solver with Application to Photorealistic Style Transfer"
date: 2018-06-13 22:05:35
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Gradient_Descent
author: Gilles Puy, Patrick P&#xe9;rez
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new flexible deep convolutional neural network (convnet) to perform fast visual style transfer. In contrast to existing convnets that address the same task, our architecture derives directly from the structure of the gradient descent originally used to solve the style transfer problem [Gatys et al., 2016]. Like existing convnets, ours approximately solves the original problem much faster than the gradient descent. However, our network is uniquely flexible by design: it can be manipulated at runtime to enforce new constraints on the final solution. In particular, we show how to modify it to obtain a photorealistic result with no retraining. We study the modifications made by [Luan et al., 2017] to the original cost function of [Gatys et al., 2016] to achieve photorealistic style transfer. These modifications affect directly the gradient descent and can be reported on-the-fly in our network. These modifications are possible as the proposed architecture stems from unrolling the gradient descent.

##### Abstract (translated by Google)
我们提出了一种新的灵活的深度卷积神经网络（convnet）来执行快速的视觉样式转换。与现有的可解决相同任务的小圆点相反，我们的架构直接来自最初用于解决样式转移问题的梯度下降结构[Gatys et al。，2016]。像现有的小圆点一样，我们大约比梯度下降快得多地解决了原始问题。但是，我们的网络具有独特的设计灵活性：可以在运行时对其进行操作，以对最终解决方案实施新的约束。特别是，我们展示了如何修改它以获得没有再培训的照片级逼真效果。我们研究了[Luan等人，2017]对[Gatys等人，2016]的原始成本函数进行的修改以实现照片级逼真风格的转换。这些修改直接影响梯度下降，并可以在我们的网络中实时报告。这些修改是可能的，因为所提出的体系结构源于展开渐变下降。

##### URL
[http://arxiv.org/abs/1806.05285](http://arxiv.org/abs/1806.05285)

##### PDF
[http://arxiv.org/pdf/1806.05285](http://arxiv.org/pdf/1806.05285)

